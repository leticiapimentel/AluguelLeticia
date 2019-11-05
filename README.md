pragma solidity 0.5.12;

contract AluguelLeticia {
    
    string public Locatario;
    string public Locador;
    string public FinalidadeDaLocacaoNaoResidencial;
    uint256 private valor;
    uint256 public DataDeVencimento;
    uint256 public DataDePagamento;
    address payable private contaLocatario;
        // a conta eh do locatario pq o dinheiro sai da conta dele?
    uint256 constant public Multa;
    
    constructor (string memory nomeLocatario,
    string memory nomeLocador,
    string memory _FinalidadeDaLocacaoNaoResidencial,
    uint256 memory valorDoAluguel,
    uint256 memory DataDeVencimentoDoAluguel,
    address payable memory _contaLocatario,
    uint256 constant memory valorMulta
    ) public
    {
        Locatario = nomeLocatario;
        Locador = nomeLocador;
        FinalidadeDaLocacaoNaoResidencial = _FinalidadeDaLocacaoNaoResidencial;
        DataDeVencimento = DataDeVencimentoDoAluguel;
        DataDePagamento = DataDePagamentoDoAluguel;
        valor = valorDoAluguel;
        contaLocatario = _contaLocatario;
        Multa = valorDaMulta;
        valorDaMulta = 3*valorDoAluguel;
        
    
    function AplicacaoMultaAtrasoNoPagamento (uint256 DataDePagamentoDoAluguel)
    public {
    if (DataDePagamentoDoAluguel > DataDeVencimentoDoAluguel == Multa)}
    
    {
    function FinalidadeDaLocacaoNaoResidencial (string public _FinalidadeDaLocacaoNaoResidencial) 
    public {
    require (FinalidadeDaLocacaoNaoResidencial = PrestarServicosEducacionais, "Objeto Inválido")
    
    }    
    
    
}

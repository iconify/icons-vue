<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#iMvTABe)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="umfrftwnu"/><path fill="url(#iqdGPbc)" class="umfrftwnu"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#imeBJxc)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#ivHxkxb)"><path class="zvdkucbqp"/></g><g filter="url(#innRWNe)"><path fill="url(#iMm4Ddd)" class="u0ana6wkh"/><path fill="url(#ideVytc)" class="u0ana6wkh"/><path fill="url(#iNjTTxJ)" class="u0ana6wkh"/></g><path fill="url(#iI9K8nc)" class="u0ana6wkh"/><g filter="url(#i0BlKkO)"><path class="gdlbulygy"/></g><g filter="url(#ilehj4J)"><path fill="url(#itFU7Nd)" class="vvnobeb4d"/><path fill="url(#ipIpBme)" class="vvnobeb4d"/></g><path fill="url(#ix1PWyN)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#iqUNw9c)" class="gael-ox4b"/><path fill="url(#iDW3OSc)" class="gael-ox4b"/><g filter="url(#ijciAOb)"><path fill="url(#iMNODVc)" class="v6z_k_d_d"/></g><g filter="url(#iE7kNZb)"><path fill="url(#iqg4eKe)" class="qckr5_bvx"/></g><g filter="url(#iCGUzqe)"><path class="od16rgzdk"/></g><g filter="url(#ifSdiWc)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#i4tZ6dB)" class="p_c3lrfef"/><path fill="url(#iq55ikc)" class="p1mpdub5r"/><path fill="url(#ih5s2Zg)" class="j2ox3-cig"/><path fill="url(#ioiBYBc)" class="gdj23o45a"/><g filter="url(#iYpeeSf)"><path fill="url(#iiygSKc)" class="iuj_uwbkx"/><path fill="url(#iA46VQd)" class="iuj_uwbkx"/></g><path fill="url(#ivYJwKn)" class="iuj_uwbkx"/><path fill="url(#iarUxUR)" class="iuj_uwbkx"/><path fill="url(#idIAcgc)" class="iuj_uwbkx"/><path fill="url(#ijoDSJn)" class="iuj_uwbkx"/><path fill="url(#iNoFo2c)" class="iuj_uwbkx"/><path fill="url(#iwjSQQd)" class="iuj_uwbkx"/><path fill="url(#iTWd4Oe)" class="iuj_uwbkx"/><path fill="url(#i44BOZd)" class="iuj_uwbkx"/><path fill="url(#iEaf6Wb)" class="iuj_uwbkx"/><g filter="url(#iemn5kc)"><path class="jl71g2byw"/></g><g filter="url(#i7YAvqd)"><path class="fua5coyea"/><path fill="url(#iCxCGdd)" class="wiyvd0ymb"/><path fill="url(#iT43HSc)" class="wiyvd0ymb"/><path fill="url(#iYwLIyc)" class="wiyvd0ymb"/><path fill="url(#iXXsC4q)" class="wiyvd0ymb"/><path fill="url(#ir6NoPd)" class="wiyvd0ymb"/></g><path fill="url(#i8RpnBc)" class="wiyvd0ymb"/><path fill="url(#iXoXOPd)" class="wiyvd0ymb"/><g filter="url(#iOFNG8c)"><path stroke="url(#iOwvEIA)" class="x5dsl11oe"/></g><path fill="url(#iIoLSdd)" class="u1-a-970u"/><path class="i1jy5d_qf"/><path fill="url(#ijV8z1d)" class="plmppmbxv"/><path class="xm2mf-bwp"/><g filter="url(#iSVIzRc)"><path class="akt43w7yk"/><path fill="url(#izSYNFb)" class="r6kbtq_6g"/></g><g filter="url(#i7Ow2Im)"><path fill="url(#i2YsU0b)" class="ol1-l7u5a"/></g><path class="hvl6iv-td"/><path fill="url(#iVGqx4m)" class="iye4_fbnn"/><path class="fk5tucw5b"/><g filter="url(#ippwPxd)"><path fill="url(#i5PHg4D)" class="oal8hz3md"/></g><g filter="url(#iQM0Nkd)"><ellipse transform="rotate(-27.914 13.53 9.834)" class="dv3hlvbjd"/><ellipse fill="url(#iwIrDeb)" transform="rotate(-27.914 13.53 9.834)" class="poba5z9hy"/></g><path fill="url(#iGvPDGb)" class="m_hwpbb3p"/><path fill="url(#irfC5nd)" class="m_hwpbb3p"/><path fill="url(#ioVkKkV)" class="m_hwpbb3p"/><path fill="url(#i7rXGPc)" class="m_hwpbb3p"/><path fill="url(#iSAyEyd)" class="i1fsg_bua"/><path fill="url(#iqiD4Hb)" class="i1fsg_bua"/><g filter="url(#i8E4DQb)"><path fill="url(#iZ9pIVd)" class="q8c0o46sy"/></g><g filter="url(#iF1eXVb)"><path fill="url(#iea99ic)" class="pph9rzbfz"/></g><path fill="url(#iMe0HZc)" class="qvivknb0c"/><path fill="url(#iLreRab)" class="qvivknb0c"/><path fill="url(#iLN7jod)" class="qvivknb0c"/><g filter="url(#ivD9rTd)"><path fill="url(#iUWHaRL)" class="gio200bup"/></g><path fill="url(#iX4wzpc)" class="mr7tpbbng"/><path fill="url(#iKu0fib)" class="mr7tpbbng"/><path fill="url(#iMJWaPd)" class="mr7tpbbng"/><g filter="url(#iEGdvob)"><path class="fgsk7lbfw"/></g><g filter="url(#iMO2mHN)"><path fill="url(#ima9okd)" class="u82_zobtn"/><path fill="url(#iIwwRze)" class="u82_zobtn"/></g><g filter="url(#iML95ad)"><path fill="url(#iDJ9V0w)" class="h4jgozbmm"/></g><g filter="url(#ijXS4ud)"><path fill="url(#iGflDkc)" class="ll6v6sbuj"/></g><path fill="url(#ioY443d)" class="ll6v6sbuj"/><defs><radialGradient id="iMvTABe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.403)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ipIpBme" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.868)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="ix1PWyN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="dsfnryq2l"/><stop offset="1" class="e3skdu--u"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iqg4eKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.41287 -1.9196 0 16.005 17.153)" gradientUnits="userSpaceOnUse"><stop class="hh-phx-8a"/><stop offset="1" class="h8ftowbgb"/></radialGradient><radialGradient id="iq55ikc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2415 1.95344 -.67327 -.08323 21.726 7.241)" gradientUnits="userSpaceOnUse"><stop class="cdfbv26hw"/><stop offset="1" class="vffww2mcn"/></radialGradient><radialGradient id="ih5s2Zg" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.897 20.796)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="ioiBYBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.927 12.278)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iiygSKc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.791 10.847)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iA46VQd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.55 8.125)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iarUxUR" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.875 -11.6852 0 16.03 9.38)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="st74h0ata"/><stop offset=".887" class="bi6uxe1jq"/><stop offset="1" class="odeawb7eb"/></radialGradient><radialGradient id="idIAcgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.43 9.534)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="ijoDSJn" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09428 1.19083 .00428 13.683 9.58)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iNoFo2c" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.521 6.223)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iwjSQQd" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.192 8.114)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iTWd4Oe" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.155 13.765)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i44BOZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.768 10.351)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iEaf6Wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46327 -5.47964 0 16.03 7.935)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="x2b-eddvk"/><stop offset="1" class="p_k4zebii"/></radialGradient><radialGradient id="iT43HSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.45 12.207)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iXXsC4q" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.566 11.638)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iXoXOPd" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.935 8.962)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iIoLSdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.492 14.47)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ijV8z1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.166 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="izSYNFb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.421 .615)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVGqx4m" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.802 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iwIrDeb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.515 10.149)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irfC5nd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.601 9.944)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="ioVkKkV" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.962 10.489)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i7rXGPc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.076 10.661)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iqiD4Hb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.068 10.585)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iZ9pIVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.068 10.587)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iMe0HZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.475 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iLreRab" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.788 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iLN7jod" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.37 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iUWHaRL" cx="0" cy="0" r="1" gradientTransform="matrix(-.40626 -3.49726 14.5441 -1.6895 18.59 8.9)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iKu0fib" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.089 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iMJWaPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.089 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="iIwwRze" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.67 -1.204)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iGflDkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.573 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="ioY443d" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.87 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iI9K8nc" x1="13.295" x2="13.295" y1="29.69" y2="23.357" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="iqUNw9c" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iDW3OSc" x1="18.442" x2="17.099" y1="16.497" y2="18.247" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="i4tZ6dB" x1="10.347" x2="11.067" y1="7.888" y2="7.888" gradientUnits="userSpaceOnUse"><stop class="y5gfhwpsk"/><stop offset="1" class="d9wizsnam"/></linearGradient><linearGradient id="ivYJwKn" x1="21.141" x2="18.612" y1="12.532" y2="12.532" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iCxCGdd" x1="16.822" x2="15.983" y1="11.521" y2="11.556" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iYwLIyc" x1="15.983" x2="15.983" y1="12.661" y2="12.196" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ir6NoPd" x1="15.983" x2="15.983" y1="9.956" y2="10.502" gradientUnits="userSpaceOnUse"><stop class="pzyus7blf"/><stop offset="1" class="w75wl1yit"/></linearGradient><linearGradient id="i8RpnBc" x1="16.399" x2="16.399" y1="12.798" y2="12.606" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="iOwvEIA" x1="14.782" x2="15.1" y1="14.231" y2="13.397" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="i2YsU0b" x1="18.943" x2="18.63" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5PHg4D" x1="14.545" x2="14.232" y1="9.984" y2="10.177" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGvPDGb" x1="22.42" x2="21.213" y1="10.011" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iSAyEyd" x1="10.134" x2="11.592" y1="10.715" y2="10.588" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iea99ic" x1="21.437" x2="21.437" y1="9.702" y2="11.46" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iX4wzpc" x1="17.339" x2="11.12" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="ima9okd" x1="16.081" x2="14.503" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iDJ9V0w" x1="18.073" x2="16.587" y1="3.169" y2="4.16" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient><filter id="imeBJxc" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".5"/></filter><filter id="ivHxkxb" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".5"/></filter><filter id="innRWNe" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2464" result="effect2_innerShadow_4002_2464"/></filter><filter id="i0BlKkO" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".5"/></filter><filter id="ilehj4J" width="3.042" height="14.123" x="18.465" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2464" result="effect2_innerShadow_4002_2464"/></filter><filter id="ijciAOb" width="2.735" height="2.58" x="14.632" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2464" result="effect2_innerShadow_4002_2464"/></filter><filter id="iE7kNZb" width="3.989" height="1.699" x="13.935" y="16.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.258824 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/></filter><filter id="iCGUzqe" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".1"/></filter><filter id="ifSdiWc" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2464" result="effect2_innerShadow_4002_2464"/></filter><filter id="iYpeeSf" width="11.22" height="12.442" x="10.92" y="4.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2464" result="effect2_innerShadow_4002_2464"/></filter><filter id="iemn5kc" width="3.747" height="4.9" x="13.968" y="9.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".5"/></filter><filter id="i7YAvqd" width="2.277" height="3.3" x="14.845" y="9.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".1"/></filter><filter id="iOFNG8c" width="3.718" height="1.573" x="14.124" y="13.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".05"/></filter><filter id="iSVIzRc" width=".787" height=".696" x="17.431" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".05"/></filter><filter id="i7Ow2Im" width=".891" height=".913" x="18.271" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".1"/></filter><filter id="ippwPxd" width=".986" height="1.04" x="13.828" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".1"/></filter><filter id="iQM0Nkd" width=".913" height=".704" x="13.074" y="9.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".05"/></filter><filter id="i8E4DQb" width="1.329" height="2.379" x="9.903" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".125"/></filter><filter id="iF1eXVb" width="1.806" height="2.758" x="20.534" y="9.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".25"/></filter><filter id="ivD9rTd" width="10.9" height="2.77" x="10.545" y="6.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/></filter><filter id="iEGdvob" width="4.831" height="2.64" x="13.58" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2464" stdDeviation=".125"/></filter><filter id="iMO2mHN" width="2.293" height="1.21" x="13.851" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/></filter><filter id="iML95ad" width="2.298" height="1.22" x="15.933" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/></filter><filter id="ijXS4ud" width="1.63" height="1.63" x="15.285" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2464"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pilot-medium" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.akt43w7yk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.102 9.642c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bi6uxe1jq {
  stop-color: var(--svg-color--995f76, #995F76);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.cdfbv26hw {
  stop-color: var(--svg-color--624746, #624746);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d9wizsnam {
  stop-color: var(--svg-color--3f2b2c, #3F2B2C);
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dsfnryq2l {
  stop-color: var(--svg-color--c0aac0, #C0AAC0);
}

.dv3hlvbjd {
  cx: 13.53px;
  cy: 9.834px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3skdu--u {
  stop-color: var(--svg-color--928392, #928392);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fgsk7lbfw {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.783 4.352h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.005l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.fk5tucw5b {
  fill: var(--svg-color--000, #000);
  d: path("M14.31 10.346a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.fs1ufx2tc {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348H13.49v4.74c0 .31.334.49.566.29l1.95-1.67l1.948 1.67c.232.2.567.02.567-.29v-4.74z");
}

.ft5dv1b6b {
  fill: none;
}

.fua5coyea {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.601 10.132l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gdj23o45a {
  d: path("M11.122 12.097a1.64 1.64 0 0 1-.905-.309v.931c0 .893.533 1.689 1.341 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.gdlbulygy {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.48l.444 1.049c.202.26.272.65.178 1.01l-1.295 4.646l-.22-10.446l.09-.183q.507.174.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.gio200bup {
  d: path("M15.995 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h4jgozbmm {
  d: path("M16.087 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.h8ftowbgb {
  stop-color: var(--svg-color--9a5f76, #9A5F76);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hh-phx-8a {
  stop-color: var(--svg-color--904d71, #904D71);
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.hvl6iv-td {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.593 9.182c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i1fsg_bua {
  d: path("M10.94 8.983a1.62 1.62 0 0 0-1.393 1.598c0 .86.673 1.56 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.i1jy5d_qf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.374 9.182c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341H17.23a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iuj_uwbkx {
  d: path("M11.158 13.611a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.883.237-3.76.325-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418H14.26c-1.845 0-3.34 1.512-3.34 3.379c0 1.86.115 3.691.237 5.556");
}

.iye4_fbnn {
  d: path("M13.8 9.453a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j2ox3-cig {
  d: path("M20.845 12.097a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019a4.1 4.1 0 0 0 .345-1.18z");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jl71g2byw {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.582 10.328l-.59 1.838c-.102.378.14.756.483.756h.732c.343 0 .586-.384.485-.756l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll6v6sbuj {
  d: path("M16.075 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.m_hwpbb3p {
  d: path("M20.905 12.188q.1-1.597.185-3.192a1.61 1.61 0 0 1-.185 3.191");
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mr7tpbbng {
  d: path("M15.945 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.oal8hz3md {
  d: path("M14.615 10.24c0-.288-.235-.48-.298-.538l-.289.279l.178.361z");
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od16rgzdk {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.329h-.592c-.124 0-.23.09-.239.22c-.01.129.096.248.22.248h.152c.18 0 .18.08.213.15c.057.12.172.2.306.2h.238l.54.128c.133 0 .46-.099.518-.218l.086-.2c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.249-.238-.249");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odeawb7eb {
  stop-color: var(--svg-color--964f84, #964F84);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.ol1-l7u5a {
  d: path("M18.962 10.228a.84.84 0 0 0-.23-.463l-.26.286l.116.228z");
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p_c3lrfef {
  d: path("M10.347 6.319h.719v3.752h-.719z");
}

.p_k4zebii {
  stop-color: var(--svg-color--834f63, #834F63);
  stop-opacity: 0;
}

.p1mpdub5r {
  d: path("M21.007 6.29h.72v3.752H20.68z");
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plmppmbxv {
  d: path("M18.168 9.453a.893.893 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.poba5z9hy {
  cx: 13.53px;
  cy: 9.834px;
  rx: 0.39px;
  ry: 0.197px;
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pph9rzbfz {
  d: path("M21.034 11.46a333 333 0 0 0 .094-1.758c.401.054.712.426.712.876c0 .484-.36.878-.806.882");
}

.pzyus7blf {
  stop-color: var(--svg-color--936367, #936367);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q8c0o46sy {
  d: path("M10.898 9.648a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qckr5_bvx {
  d: path("M16.005 18.445c1.789-.788 1.932-1.316 1.919-1.7h-3.838c-.013.384.224.97 1.919 1.7");
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvivknb0c {
  d: path("M21.737 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r6kbtq_6g {
  d: path("M18.102 9.642c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.st74h0ata {
  stop-color: var(--svg-color--995f76, #995F76);
  stop-opacity: 0;
}

.sv13rb7yi {
  stop-color: var(--svg-color--68565a, #68565A);
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.u0ana6wkh {
  d: path("M13.295 15.837q-.691.176-1.345.436l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.u1-a-970u {
  d: path("M15.984 13.743c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.28-.198-.21a3 3 0 0 1-1.386.329");
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.u82_zobtn {
  d: path("M16.035 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.umfrftwnu {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.377");
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v6z_k_d_d {
  d: path("m14.732 19.661l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.141h-1.022a.24.24 0 0 1-.216-.141z");
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.vffww2mcn {
  stop-color: var(--svg-color--4f3636, #4F3636);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vvnobeb4d {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V16.05l.117-.182q.653.173 1.272.423l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w75wl1yit {
  stop-color: var(--svg-color--936367, #936367);
  stop-opacity: 0;
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wiyvd0ymb {
  d: path("m15.601 10.132l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.x2b-eddvk {
  stop-color: var(--svg-color--834f63, #834F63);
}

.x5dsl11oe {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.633 13.348h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.044c-.39.203-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xm2mf-bwp {
  fill: var(--svg-color--000, #000);
  d: path("M17.656 10.346a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y5gfhwpsk {
  stop-color: var(--svg-color--57413f, #57413F);
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zvdkucbqp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.271c-.54.783-1.546 2.199-1.85 2.873c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>

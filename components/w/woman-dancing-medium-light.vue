<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifEazde)"><path fill="url(#iO3LxNd)" class="sbhmekbbs"/><path fill="url(#i56sd0a)" class="sbhmekbbs"/><path fill="url(#iyfXhQB)" class="sbhmekbbs"/><path fill="url(#iMgZcmc)" class="sbhmekbbs"/><path fill="url(#ilicT0b)" class="sbhmekbbs"/><path fill="url(#iCtUOAe)" class="sbhmekbbs"/><path fill="url(#i4nXPic)" class="sbhmekbbs"/></g><path fill="url(#i4Wc1Fe)" class="uwqjkbvol"/><path fill="url(#imd4NIb)" class="uwqjkbvol"/><path fill="url(#i1Vpllf)" class="uwqjkbvol"/><g filter="url(#iWaxxre)"><path class="krf_f0b6z"/></g><g filter="url(#iNz1TTd)"><path class="u8l8bnbbx"/></g><path fill="url(#iO54W6c)" class="ifk4wkbgx"/><path fill="url(#ijOs7Yc)" class="ifk4wkbgx"/><path fill="url(#i1ynvbt)" class="a2ysf6bzt"/><g filter="url(#i201cbY)"><path class="gm8j-crmz"/><path fill="url(#iylL1yd)" class="o5cnyqbgj"/><path fill="url(#ioQwuse)" class="o5cnyqbgj"/></g><g filter="url(#i9DgDPQ)"><path fill="url(#iLuyZJb)" class="e648o_baz"/><path fill="url(#ikP0P5c)" class="e648o_baz"/><path fill="url(#iLMCzNd)" class="e648o_baz"/><path fill="url(#i8uPQSc)" class="e648o_baz"/><path fill="url(#i4DOhAc)" class="e648o_baz"/></g><g filter="url(#iENQRob)"><path fill="url(#i9huZKN)" class="d49vq-b3b"/><path fill="url(#i60rmed)" class="d49vq-b3b"/><path fill="url(#i3wkpUc)" class="d49vq-b3b"/></g><path fill="url(#iW7Dhmc)" class="d49vq-b3b"/><path fill="url(#iLbqbCd)" class="d49vq-b3b"/><g filter="url(#inv0Ddc)"><path class="d2bzcgumt"/></g><g filter="url(#iO6FlMC)"><path class="n4cgu8b4a"/><path fill="url(#iEQ0xCb)" class="bds0mc2jk"/></g><path fill="url(#iQNho6o)" class="ws5-tkbbq"/><path fill="url(#iDpvIib)" class="ws5-tkbbq"/><g filter="url(#i3URvEe)"><path fill="url(#iPsIjyc)" class="dn8sk7b7d"/></g><path fill="url(#icRf2ec)" class="kwcf4flcv"/><g filter="url(#iqCHEOd)"><path fill="url(#it1EQ7b)" class="i0qq1wblx"/></g><g filter="url(#iLAbise)"><path fill="url(#igsIbQd)" class="t_3eddbyn"/></g><path fill="url(#iukBjMd)" class="ynticpbfc"/><path fill="url(#icw6ygb)" class="ynticpbfc"/><path fill="url(#iwptDvc)" class="ynticpbfc"/><path fill="url(#i2HN5Pc)" class="ynticpbfc"/><path fill="url(#iQBQXWb)" class="ynticpbfc"/><path fill="url(#iCY3Npb)" class="ynticpbfc"/><path fill="url(#iPblwob)" class="ynticpbfc"/><path fill="url(#ih5zEZc)" class="ynticpbfc"/><g filter="url(#iTUeEEe)"><path class="qyq5h-jrz"/></g><path class="ypcbyhbui"/><path fill="url(#ily0Wrb)" class="o59cz6b0z"/><path fill="url(#iQvQNEc)" class="o59cz6b0z"/><path fill="url(#iHkZ3Lo)" class="o59cz6b0z"/><path fill="url(#ieM1mVc)" class="o59cz6b0z"/><path fill="url(#iUgmGBc)" class="o59cz6b0z"/><g filter="url(#icaRddc)"><path stroke="url(#i40Ml5b)" class="n25i9mbre"/></g><path class="q3e93811r"/><g filter="url(#iLuBnFe)"><path class="pwjuhq5xz"/></g><g filter="url(#i2jmClc)"><path class="hau5xcu7k"/></g><g filter="url(#iasNLHc)"><path class="t9lx25bgr"/></g><g filter="url(#iyMs1ZC)"><path clip-rule="evenodd" class="t8p_nhwqa"/></g><path class="fk7t7zb-y"/><path fill="url(#iszVLqY)" class="in2gs6jqz"/><path class="m6-r9hb4c"/><g filter="url(#iNDERQc)"><path class="yskuwwbra"/><path fill="url(#ic1Awtk)" class="nn0drmzdc"/></g><g filter="url(#icJOudb)"><path fill="url(#iTPhICc)" class="z1qtb2bfq"/></g><path class="o7mqan3qw"/><path fill="url(#ix8b0YH)" class="m24m42b2x"/><path class="et06rcc2a"/><g filter="url(#iQotztb)"><path fill="url(#iikdtEd)" class="jyuyzmbrn"/></g><g filter="url(#iojdYkb)"><ellipse transform="rotate(-27.914 11.188 5.778)" class="tg25wbqgg"/><ellipse fill="url(#iQh9b2E)" transform="rotate(-27.914 11.188 5.778)" class="vzbwqpbmt"/></g><g filter="url(#iwfi5Zd)"><path class="g_wu8dbnz"/></g><g filter="url(#i3syqCc)"><path class="dm52tbwoi"/></g><g filter="url(#i1uWVce)"><path fill="url(#iIlBree)" class="v3i-1pmwj"/></g><g filter="url(#iRuMX4c)"><path fill="url(#iUZWmmb)" class="berq-ybis"/></g><g filter="url(#ipZr4Ec)"><path fill="url(#ihAp9nV)" class="mx0e40buh"/><path fill="url(#ioY8Ghd)" class="mx0e40buh"/><path fill="url(#i1sigyb)" class="mx0e40buh"/></g><g filter="url(#itnEtyC)"><path fill="url(#iaPypic)" clip-rule="evenodd" class="kkds9sbif"/></g><g filter="url(#iZ6kdze)"><path fill="url(#iJGx8Rc)" clip-rule="evenodd" class="ga74agm1p"/></g><defs><radialGradient id="iO3LxNd" cx="0" cy="0" r="1" gradientTransform="rotate(89.146 5.717 8.191)scale(8.28655 7.76825)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="pquvpov8y"/><stop offset="1" class="ols1i2kaq"/></radialGradient><radialGradient id="i56sd0a" cx="0" cy="0" r="1" gradientTransform="matrix(.01235 -1.33162 3.323 .03082 12.476 4.67)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="st4hs763z"/><stop offset="1" class="rl7em7bjk"/></radialGradient><radialGradient id="iyfXhQB" cx="0" cy="0" r="1" gradientTransform="matrix(.72873 1.12201 -1.51647 .98492 11.044 2.217)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="zn1rvob2u"/><stop offset="1" class="fzv28epeh"/></radialGradient><radialGradient id="iMgZcmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.07501 -1.20832 1.47894 2.53975 14.094 8.148)" gradientUnits="userSpaceOnUse"><stop class="kawgt3bsr"/><stop offset="1" class="tgd5bcc3y"/></radialGradient><radialGradient id="ilicT0b" cx="0" cy="0" r="1" gradientTransform="rotate(108.133 .467 9.637)scale(2.69863 2.03245)" gradientUnits="userSpaceOnUse"><stop class="ynngk8bxm"/><stop offset="1" class="s1hry0blp"/></radialGradient><radialGradient id="iCtUOAe" cx="0" cy="0" r="1" gradientTransform="rotate(140.722 3.181 6.715)scale(5.29739 2.1975)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="grlhkzb5c"/><stop offset="1" class="m62n6lejs"/></radialGradient><radialGradient id="i4nXPic" cx="0" cy="0" r="1" gradientTransform="rotate(140.56 3.908 5.872)scale(3.41829 2.98525)" gradientUnits="userSpaceOnUse"><stop class="jpih75bxh"/><stop offset="1" class="bkzx2xbnc"/></radialGradient><radialGradient id="i1Vpllf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72861 4.02946 -1.91414 -.82115 8.63 27.856)" gradientUnits="userSpaceOnUse"><stop class="rxdm1gb4b"/><stop offset="1" class="en9rkbb0o"/></radialGradient><radialGradient id="i1ynvbt" cx="0" cy="0" r="1" gradientTransform="rotate(117.071 -3.416 17.085)scale(2.08793 1.98277)" gradientUnits="userSpaceOnUse"><stop class="u6ezkbbkd"/><stop offset="1" class="cpmw12bkg"/></radialGradient><radialGradient id="iylL1yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.61426 -1.61513 0 20.377 7.221)" gradientUnits="userSpaceOnUse"><stop class="uh03xc5sy"/><stop offset="1" class="ijs6qib6n"/></radialGradient><radialGradient id="ioQwuse" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 9.82 4.868)scale(.67604 .47453)" gradientUnits="userSpaceOnUse"><stop class="rvjiiobzz"/><stop offset="1" class="ifwlopgfz"/></radialGradient><radialGradient id="iLuyZJb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.18747 -5.71878 5.09832 -4.62466 15.278 14.836)" gradientUnits="userSpaceOnUse"><stop class="zstr-2b3h"/><stop offset="1" class="r38-lhbhs"/></radialGradient><radialGradient id="ikP0P5c" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -.45703 .8012 5.4783 9.84 12.324)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="dz8dqqbnh"/><stop offset="1" class="hv09-7aho"/></radialGradient><radialGradient id="iLMCzNd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 0 0 -4.28125 16.153 9.867)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="d1nygi1_s"/><stop offset="1" class="bzjd0s3dz"/></radialGradient><radialGradient id="i8uPQSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14245 .25001 -.22815 -1.9551 15.952 12.71)" gradientUnits="userSpaceOnUse"><stop class="etzb8g0rx"/><stop offset="1" class="q_d1lub6r"/></radialGradient><radialGradient id="i4DOhAc" cx="0" cy="0" r="1" gradientTransform="rotate(91.112 2.088 9.266)scale(2.8878 5.12554)" gradientUnits="userSpaceOnUse"><stop class="ed0bwz-2w"/><stop offset="1" class="h1j4vebkc"/></radialGradient><radialGradient id="i9huZKN" cx="0" cy="0" r="1" gradientTransform="rotate(45.496 -14.752 21.43)scale(10.2092 15.8767)" gradientUnits="userSpaceOnUse"><stop class="h84ffkb2i"/><stop offset="1" class="emq3pu1ym"/></radialGradient><radialGradient id="i3wkpUc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -4.4375 3.8181 .75287 27.06 16.648)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="c4hclxboa"/><stop offset="1" class="mz51gmfzq"/></radialGradient><radialGradient id="iW7Dhmc" cx="0" cy="0" r="1" gradientTransform="matrix(4.72488 -2.8426 6.67598 11.09657 4.788 29.252)" gradientUnits="userSpaceOnUse"><stop class="ket8l8b0j"/><stop offset="1" class="lze6x5b3f"/></radialGradient><radialGradient id="iLbqbCd" cx="0" cy="0" r="1" gradientTransform="matrix(.81156 -4.64805 2.43505 .42516 28.216 17.497)" gradientUnits="userSpaceOnUse"><stop class="m8u-j2bfh"/><stop offset="1" class="xbj9zzvwg"/></radialGradient><radialGradient id="iEQ0xCb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31249 1.60939 -.35465 -.72996 11.236 9.283)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="cq3b8vb9s"/><stop offset="1" class="f0r-5jw2h"/></radialGradient><radialGradient id="iQNho6o" cx="0" cy="0" r="1" gradientTransform="matrix(-.80887 -1.87683 2.42187 -1.04377 13.58 10.361)" gradientUnits="userSpaceOnUse"><stop class="deirb3k3j"/><stop offset="1" class="uq-36861a"/></radialGradient><radialGradient id="iDpvIib" cx="0" cy="0" r="1" gradientTransform="rotate(47.291 -3.816 17.657)scale(1.79682 5.00055)" gradientUnits="userSpaceOnUse"><stop class="vvmjs9bob"/><stop offset="1" class="yz2fjsnhb"/></radialGradient><radialGradient id="icRf2ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.52493 .51875 -.35598 -.36022 15.15 5.774)" gradientUnits="userSpaceOnUse"><stop class="ga8awzqfa"/><stop offset="1" class="j391rbtek"/></radialGradient><radialGradient id="it1EQ7b" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.244 10.346)scale(.50175)" gradientUnits="userSpaceOnUse"><stop class="ok0xogb6i"/><stop offset="1" class="a680lr2dp"/></radialGradient><radialGradient id="igsIbQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.19762 .64844 -.64844 -.19762 9.981 5.975)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="vopejgz3x"/><stop offset="1" class="shpp5nbho"/></radialGradient><radialGradient id="iukBjMd" cx="0" cy="0" r="1" gradientTransform="rotate(141.436 5.858 5.23)scale(4.129 3.09194)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="fs81_6bpu"/><stop offset=".755" class="yiq9sac5t"/></radialGradient><radialGradient id="icw6ygb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.54891 -4.68101 0 12.335 5.342)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="rau17bcwj"/><stop offset="1" class="dbc20iija"/></radialGradient><radialGradient id="iwptDvc" cx="0" cy="0" r="1" gradientTransform="rotate(114.376 4.795 5.853)scale(1.73569 1.62623)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="mmf02ltsv"/><stop offset="1" class="otc9m4bci"/></radialGradient><radialGradient id="i2HN5Pc" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 6.537 4.397)scale(1.12362 1.78808)" gradientUnits="userSpaceOnUse"><stop class="ew0uim6gn"/><stop offset="1" class="cj7sibb8n"/></radialGradient><radialGradient id="iQBQXWb" cx="0" cy="0" r="1" gradientTransform="matrix(.75342 1.04235 -3.9863 2.88137 10.858 3.934)" gradientUnits="userSpaceOnUse"><stop class="ryea0ookf"/><stop offset="1" class="ko_af4_wq"/></radialGradient><radialGradient id="iCY3Npb" cx="0" cy="0" r="1" gradientTransform="rotate(134.662 5.878 5.092)scale(1.94408 1.24672)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="w5pmvqbyv"/><stop offset="1" class="dw874cmcb"/></radialGradient><radialGradient id="iPblwob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55272 .87076 0 13.415 5.581)" gradientUnits="userSpaceOnUse"><stop class="a9by5rbfj"/><stop offset="1" class="p98xi8b4g"/></radialGradient><radialGradient id="ih5zEZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71637 .72872 0 11.228 5.544)" gradientUnits="userSpaceOnUse"><stop class="d6gk4jb3c"/><stop offset="1" class="xv_mpdbhn"/></radialGradient><radialGradient id="iQvQNEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37671 0 0 -.11772 12.531 6.805)" gradientUnits="userSpaceOnUse"><stop class="ph4flqb3k"/><stop offset="1" class="h7fgkmbjb"/></radialGradient><radialGradient id="iHkZ3Lo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31037 .82628 0 12.335 7.054)" gradientUnits="userSpaceOnUse"><stop class="ieyztivmt"/><stop offset="1" class="jkdewyb8l"/></radialGradient><radialGradient id="iszVLqY" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 5.287 6.455)scale(.43779 .69447)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="ic1Awtk" cx="0" cy="0" r="1" gradientTransform="matrix(-.10788 -.13901 .19139 -.14853 13.247 5.862)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ix8b0YH" cx="0" cy="0" r="1" gradientTransform="matrix(-.24855 .3604 -.5717 -.39428 11.564 5.767)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iQh9b2E" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 8.507 -2.541)scale(.22984 .27628)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIlBree" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5686 1.27218 -.4918 -.6064 10.895 3.625)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="apmdt3x3q"/><stop offset=".77" class="s2wvo_jzf"/></radialGradient><radialGradient id="iUZWmmb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39614 1.90182 -2.45097 -3.08804 13.995 2.432)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="ciibtfg0w"/><stop offset=".961" class="nk2v8nx5g"/></radialGradient><radialGradient id="ihAp9nV" cx="0" cy="0" r="1" gradientTransform="rotate(-77.784 8.906 -5.543)scale(2.45165 6.28814)" gradientUnits="userSpaceOnUse"><stop offset=".607" class="kc79u3bwy"/><stop offset="1" class="l0z7fbvsr"/></radialGradient><radialGradient id="ioY8Ghd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00082 .05218 -.08841 -3.38993 12.974 3.276)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="mpjri6nek"/><stop offset="1" class="mfg0q5l4l"/></radialGradient><radialGradient id="i1sigyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0091 -.55087 .34334 -.62895 14.419 4.285)" gradientUnits="userSpaceOnUse"><stop class="wiiznx1ow"/><stop offset="1" class="owmsj2b8b"/></radialGradient><filter id="ifEazde" width="11.841" height="12.177" x="4.737" y="1.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.607843 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_618" result="effect2_innerShadow_4002_618"/></filter><filter id="iWaxxre" width="6.401" height="8.773" x="16.966" y="21.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.478431 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iNz1TTd" width="4.034" height="2.448" x="19.082" y="27.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.219608 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="i201cbY" width="8.253" height="7.777" x="14.731" y="2.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.388235 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_618" result="effect2_innerShadow_4002_618"/></filter><filter id="i9DgDPQ" width="7.93" height="8.273" x="9.022" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.207843 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iENQRob" width="24.323" height="17.206" x="4.092" y="13.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.27451 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.2 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_618" result="effect2_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.141176 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_618" result="effect3_innerShadow_4002_618"/></filter><filter id="inv0Ddc" width="2.218" height="2.723" x="4.396" y="15.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.4 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iO6FlMC" width="7.274" height="8.998" x="3.684" y="8.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.65098 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.462745 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_618" result="effect2_innerShadow_4002_618"/></filter><filter id="i3URvEe" width="1.603" height="1.503" x="9.395" y="5.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iqCHEOd" width="1.404" height="1.404" x="13.888" y="5.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".1"/></filter><filter id="iLAbise" width="1.204" height="1.204" x="9.554" y="5.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="iTUeEEe" width="1.377" height="1.753" x="11.571" y="5.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".125"/></filter><filter id="icaRddc" width="1.743" height=".726" x="11.464" y="7.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".025"/></filter><filter id="iLuBnFe" width="1.509" height=".6" x="12.669" y="5.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="i2jmClc" width="1.509" height=".6" x="10.493" y="5.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iasNLHc" width="1.252" height=".616" x="10.556" y="4.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iyMs1ZC" width="1.252" height=".616" x="13.087" y="4.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/></filter><filter id="iNDERQc" width=".473" height=".431" x="12.958" y="5.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="icJOudb" width=".628" height=".639" x="13.297" y="5.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".1"/></filter><filter id="iQotztb" width=".673" height=".698" x="11.222" y="5.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".1"/></filter><filter id="iojdYkb" width=".532" height=".435" x="10.922" y="5.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="iwfi5Zd" width="1.026" height=".426" x="13.116" y="4.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="i3syqCc" width="1.026" height=".426" x="10.569" y="4.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="i1uWVce" width="1.752" height="2.021" x="9.527" y="2.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="iRuMX4c" width="4.113" height="2.955" x="10.662" y="2.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.721569 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feGaussianBlur result="effect2_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="ipZr4Ec" width="4.203" height="2.805" x="10.573" y="2.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_618" stdDeviation=".05"/></filter><filter id="itnEtyC" width="2.957" height="3.037" x="12.949" y="2.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.341176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_618" result="effect2_innerShadow_4002_618"/></filter><filter id="iZ6kdze" width="1.893" height="1.933" x="13.445" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.0627451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_618" result="effect2_innerShadow_4002_618"/></filter><linearGradient id="i4Wc1Fe" x1="21.631" x2="12.192" y1="20.756" y2="31.059" gradientUnits="userSpaceOnUse"><stop class="x_atgxb_v"/><stop offset="1" class="ppa6_abwh"/></linearGradient><linearGradient id="imd4NIb" x1="9.974" x2="19.537" y1="24.594" y2="28.553" gradientUnits="userSpaceOnUse"><stop class="yung1xdgy"/><stop offset="1" class="i-td5rxsk"/></linearGradient><linearGradient id="iO54W6c" x1="11.126" x2="8.785" y1="27.476" y2="26.934" gradientUnits="userSpaceOnUse"><stop class="uh_t_cc5j"/><stop offset="1" class="c6qx4wbrc"/></linearGradient><linearGradient id="ijOs7Yc" x1="8.408" x2="8.908" y1="27.377" y2="27.659" gradientUnits="userSpaceOnUse"><stop offset=".221" class="wt_le6l3f"/><stop offset="1" class="qu5j33bza"/></linearGradient><linearGradient id="i60rmed" x1="28.216" x2="16.204" y1="17.367" y2="17.367" gradientUnits="userSpaceOnUse"><stop offset=".219" class="k2sx12b0p"/><stop offset="1" class="yu3j8mbni"/></linearGradient><linearGradient id="iPsIjyc" x1="9.678" x2="10.146" y1="5.885" y2="6.854" gradientUnits="userSpaceOnUse"><stop class="c3abnuf9m"/><stop offset="1" class="ilhfq-rgs"/></linearGradient><linearGradient id="ily0Wrb" x1="12.673" x2="12.303" y1="6.534" y2="6.552" gradientUnits="userSpaceOnUse"><stop class="bjtjc7yte"/><stop offset="1" class="uoi807b3e"/></linearGradient><linearGradient id="ieM1mVc" x1="12.368" x2="12.368" y1="7.077" y2="6.935" gradientUnits="userSpaceOnUse"><stop offset="0" class="p8im66f_y"/><stop offset="1" class="qq2gex10o"/></linearGradient><linearGradient id="iUgmGBc" x1="12.335" x2="12.335" y1="5.801" y2="6.54" gradientUnits="userSpaceOnUse"><stop class="iy-8e7b5c"/><stop offset=".824" class="io9zrqs7f"/></linearGradient><linearGradient id="i40Ml5b" x1="11.995" x2="12.206" y1="7.787" y2="7.38" gradientUnits="userSpaceOnUse"><stop class="off1fssuq"/><stop offset="1" class="g4i014bsv"/></linearGradient><linearGradient id="iTPhICc" x1="13.717" x2="13.571" y1="5.848" y2="5.938" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iikdtEd" x1="11.662" x2="11.516" y1="5.848" y2="5.937" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaPypic" x1="15.412" x2="14.05" y1="2.932" y2="5.276" gradientUnits="userSpaceOnUse"><stop class="y_ccjxb5k"/><stop offset="1" class="w39yz6l0u"/></linearGradient><linearGradient id="iJGx8Rc" x1="15.339" x2="13.856" y1="3.43" y2="4.383" gradientUnits="userSpaceOnUse"><stop class="wzt3udgik"/><stop offset="1" class="gn591vgmd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-dancing-medium-light" /></template>
<style>
.a2ysf6bzt {
  d: path("m8.196 27.901l-.004.008a1.6 1.6 0 0 0-.18.883c.043.36.309.727.784 1.04c.257.17.594.062.751-.201l1.034-1.73z");
}

.a680lr2dp {
  stop-color: var(--svg-color--d19579, #D19579);
}

.a9by5rbfj {
  stop-color: var(--svg-color--ca9281, #CA9281);
}

.apmdt3x3q {
  stop-color: var(--svg-color--f6dbaa, #F6DBAA);
}

.bds0mc2jk {
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.berq-ybis {
  d: path("M12.053 2.447c-.529-.117-1.236.463-1.29.66c.72 1.69 1.691 1.58 3.036 1.53c.747-.028.807.238.87.4c.123-2.125-1.41-2.323-2.616-2.59");
}

.bjtjc7yte {
  stop-color: var(--svg-color--e9b89b, #E9B89B);
}

.bkzx2xbnc {
  stop-color: var(--svg-color--c78b70, #C78B70);
  stop-opacity: 0;
}

.bzjd0s3dz {
  stop-color: var(--svg-color--ff4660, #FF4660);
  stop-opacity: 0;
}

.c3abnuf9m {
  stop-color: var(--svg-color--c9907a, #C9907A);
}

.c4hclxboa {
  stop-color: var(--svg-color--e73e59, #E73E59);
}

.c6qx4wbrc {
  stop-color: var(--svg-color--b56b61, #B56B61);
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.ciibtfg0w {
  stop-color: var(--svg-color--fff3bd, #FFF3BD);
}

.cj7sibb8n {
  stop-color: var(--svg-color--b4897a, #B4897A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpmw12bkg {
  stop-color: var(--svg-color--cc2e32, #CC2E32);
}

.cq3b8vb9s {
  stop-color: var(--svg-color--f3be9c, #F3BE9C);
}

.d1nygi1_s {
  stop-color: var(--svg-color--ff4660, #FF4660);
}

.d2bzcgumt {
  fill: var(--svg-color--cf8c86, #CF8C86);
  d: path("m5.324 17.383l-.35-.457l-.578-1.078l1.378-.516l.047 1.254l.2.26a.44.44 0 1 1-.697.537");
}

.d49vq-b3b {
  d: path("M26.74 13.508q-.222 0-.424.062c-.318.077-.621.221-.994.399h-.001c-.292.139-.626.298-1.043.46c-1.5.587-3.218.587-4.062.587H11.59c-1.933 0-3.534 1.566-3.559 3.499c-.007.536-.011 1.23-.011 1.79c0 1.797-1.662 3.73-2.672 4.687c-.7.664-.868 1.063-.967 1.297l-.014.034l-.02.044l.011.008a2.617 2.617 0 0 0 2.45 3.539h.965c-.499-.101-1.097-.246-1.566-.422c-1.04-.39-1.14-1.27-1.113-1.613c.02-.265.226-1.332 1.636-1.332c.95 0 2.031.064 3.022.123c.632.037 1.227.073 1.728.088c1.048.032 2.12-.065 2.57-1.215c.47-1.43.848-1.91 1.907-1.91c.493.03.872.049 1.124.062l.306.016c.7.047 1.452-.089 1.64-1.36c.211-1.421 1.067-1.552 1.672-1.53c.664.023 1.594.023 2.016-.29c.422-.312.468-.883.468-1.304s.147-1.164 1.172-1.266c1.149-.115 1.375-.36 1.532-.578c.226-.317.239-.694.187-1.266c-.07-.777.115-1.26.582-1.558c.617-.395 1.073.047 1.168.84c.023.19.052.446.085.736c.09.803.21 1.862.306 2.467v-3.618c0-.786-.615-1.43-1.39-1.474v-.002z");
}

.d6gk4jb3c {
  stop-color: var(--svg-color--cb8e81, #CB8E81);
}

.dbc20iija {
  stop-color: var(--svg-color--b97675, #B97675);
}

.deirb3k3j {
  stop-color: var(--svg-color--f6bc98, #F6BC98);
}

.dm52tbwoi {
  stroke: var(--svg-color--8e5f38, #8E5F38);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M11.47 4.994a1.1 1.1 0 0 0-.776.16");
}

.dn8sk7b7d {
  d: path("M10.146 6.854a.752.752 0 1 0 0-1.504a.752.752 0 0 0 0 1.504");
}

.dw874cmcb {
  stop-color: var(--svg-color--d19d8b, #D19D8B);
  stop-opacity: 0;
}

.dz8dqqbnh {
  stop-color: var(--svg-color--d62645, #D62645);
}

.e648o_baz {
  d: path("M9.95 14.54v1.67l5.735-.155c-.375-1.555-.368-3.258-.211-3.64c.156-.384.453-.774.476-1.29c.024-.516-.172-1-.476-1.484a3.5 3.5 0 0 1-.344-.805a.55.55 0 0 0-.513-.399h-.768c-.068 0-.109.09-.169.122l-.956.496l-1.204-.617c-.906.039-2.078.257-2.304.562c-.227.305-.25 1.008-.094 1.883s.43 1.812.648 2.36c.175.437.193 1.046.18 1.296");
}

.ed0bwz-2w {
  stop-color: var(--svg-color--921c39, #921C39);
}

.emq3pu1ym {
  stop-color: var(--svg-color--da2e3d, #DA2E3D);
}

.en9rkbb0o {
  stop-color: var(--svg-color--6c1118, #6C1118);
  stop-opacity: 0;
}

.et06rcc2a {
  fill: var(--svg-color--000, #000);
  d: path("M11.554 6.017a.24.24 0 0 0-.24-.239a.238.238 0 0 0-.212.349h.423a.24.24 0 0 0 .028-.11");
}

.etzb8g0rx {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
}

.ew0uim6gn {
  stop-color: var(--svg-color--b4897a, #B4897A);
}

.f0r-5jw2h {
  stop-color: var(--svg-color--dfab8a, #DFAB8A);
  stop-opacity: 0;
}

.fk7t7zb-y {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.452 5.473c.305 0 .563.21.633.495a.128.128 0 0 1-.125.159h-1.042A.108.108 0 0 1 12.812 6a.65.65 0 0 1 .64-.527");
}

.fs81_6bpu {
  stop-color: var(--svg-color--e8b492, #E8B492);
}

.ft5dv1b6b {
  fill: none;
}

.fzv28epeh {
  stop-color: var(--svg-color--dcca95, #DCCA95);
  stop-opacity: 0;
}

.g_wu8dbnz {
  stroke: var(--svg-color--8e5f38, #8E5F38);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M13.241 4.994c.15-.037.526-.019.776.16");
}

.g4i014bsv {
  stop-color: var(--svg-color--ce978b, #CE978B);
  stop-opacity: 0;
}

.ga74agm1p {
  fill-rule: evenodd;
  d: path("m14.718 4.488l-.004.015c-.072.222-.282.352-.47.292c-.187-.061-.28-.29-.209-.512l.008-.02h-.039c-.226 0-.409-.159-.409-.356s.183-.356.409-.356h.007L14 3.506c-.043-.221.088-.433.293-.473c.194-.037.385.094.44.296l.004-.002c.181-.134.423-.113.54.045c.116.159.064.396-.118.53l-.016.01q.03.023.056.05c.162.168.178.415.036.551c-.133.128-.356.114-.517-.025");
}

.ga8awzqfa {
  stop-color: var(--svg-color--e5b79c, #E5B79C);
}

.gm8j-crmz {
  fill: var(--svg-color--daa182, #DAA182);
  d: path("M18.847 8.508h-4.116l.555 2.203h3.508c1.486 0 2.375-1.063 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.155.784-.215a1 1 0 0 0 .508-.343l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.167-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.133.12-.417.448-.492.804a2.8 2.8 0 0 0-.028.758c.013.151.024.303.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.gn591vgmd {
  stop-color: var(--svg-color--c32e4e, #C32E4E);
}

.grlhkzb5c {
  stop-color: var(--svg-color--bd835a, #BD835A);
}

.h1j4vebkc {
  stop-color: var(--svg-color--921c39, #921C39);
  stop-opacity: 0;
}

.h7fgkmbjb {
  stop-color: var(--svg-color--e6b49a, #E6B49A);
  stop-opacity: 0;
}

.h84ffkb2i {
  stop-color: var(--svg-color--d42f4e, #D42F4E);
}

.hau5xcu7k {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M11.802 5.836c-.124-.218-.313-.39-.718-.39a.77.77 0 0 0-.502.172c-.125.102-.108.231-.011.28l.26.148c.304-.098.64-.111.97-.21");
}

.hv09-7aho {
  stop-color: var(--svg-color--d62645, #D62645);
  stop-opacity: 0;
}

.i-td5rxsk {
  stop-color: var(--svg-color--851e29, #851E29);
  stop-opacity: 0;
}

.i0qq1wblx {
  d: path("M14.59 6.604a.502.502 0 1 0 0-1.004a.502.502 0 0 0 0 1.004");
}

.ieyztivmt {
  stop-color: var(--svg-color--ca8c85, #CA8C85);
}

.ifk4wkbgx {
  d: path("m8.192 27.91l.719-1.45l2.555-.038l-1.919 3.209c-.157.263-.494.371-.751.202c-.475-.313-.741-.682-.784-1.04a1.6 1.6 0 0 1 .18-.884");
}

.ifwlopgfz {
  stop-color: var(--svg-color--e9ba9b, #E9BA9B);
  stop-opacity: 0;
}

.ijs6qib6n {
  stop-color: var(--svg-color--dd9d82, #DD9D82);
  stop-opacity: 0;
}

.ilhfq-rgs {
  stop-color: var(--svg-color--c28177, #C28177);
}

.in2gs6jqz {
  d: path("M13.355 5.6a.417.417 0 0 1 .402.527h-.805a.42.42 0 0 1 .404-.527");
}

.io9zrqs7f {
  stop-color: var(--svg-color--d9a389, #D9A389);
  stop-opacity: 0;
}

.iy-8e7b5c {
  stop-color: var(--svg-color--d9a389, #D9A389);
}

.j391rbtek {
  stop-color: var(--svg-color--d29886, #D29886);
}

.jkdewyb8l {
  stop-color: var(--svg-color--ca8c85, #CA8C85);
  stop-opacity: 0;
}

.jpih75bxh {
  stop-color: var(--svg-color--c78b70, #C78B70);
}

.jyuyzmbrn {
  d: path("M11.695 5.967c0-.134-.11-.224-.139-.25l-.134.129l.082.168z");
}

.k2sx12b0p {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
}

.kawgt3bsr {
  stop-color: var(--svg-color--e0a37b, #E0A37B);
}

.kc79u3bwy {
  stop-color: var(--svg-color--ddcd98, #DDCD98);
  stop-opacity: 0;
}

.ket8l8b0j {
  stop-color: var(--svg-color--d32659, #D32659);
}

.kkds9sbif {
  fill-rule: evenodd;
  d: path("M14.85 4.965c.013-.04.067-.057.1-.032a.599.599 0 1 0 .711-.963a.067.067 0 0 1 0-.104a.598.598 0 0 0-.705-.967c-.035.025-.09.007-.102-.034a.6.6 0 1 0-1.14.368c.014.04-.02.087-.062.087h-.004a.599.599 0 0 0 0 1.197c.04 0 .073.044.061.083a.599.599 0 0 0 1.14.365");
}

.ko_af4_wq {
  stop-color: var(--svg-color--cd9178, #CD9178);
  stop-opacity: 0;
}

.krf_f0b6z {
  fill: var(--svg-color--f2b99f, #F2B99F);
  d: path("m19.653 28.71l-2.687-5.53l1.851-1.57l3.541 8.133a.1.1 0 0 1-.092.14h-.769c-1.012 0-1.594-.586-1.844-1.172");
}

.kwcf4flcv {
  d: path("M14.59 6.854a.752.752 0 1 0 0-1.504a.752.752 0 0 0 0 1.504");
}

.l0z7fbvsr {
  stop-color: var(--svg-color--ddcd98, #DDCD98);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lze6x5b3f {
  stop-color: var(--svg-color--d32659, #D32659);
  stop-opacity: 0;
}

.m24m42b2x {
  d: path("M11.315 5.6a.417.417 0 0 0-.402.527h.806a.42.42 0 0 0-.404-.527");
}

.m6-r9hb4c {
  fill: var(--svg-color--000, #000);
  d: path("M13.117 6.017c0-.133.106-.239.238-.239a.238.238 0 0 1 .213.349h-.423a.2.2 0 0 1-.028-.11");
}

.m62n6lejs {
  stop-color: var(--svg-color--e5a785, #E5A785);
  stop-opacity: 0;
}

.m8u-j2bfh {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
}

.mfg0q5l4l {
  stop-color: var(--svg-color--f5dda4, #F5DDA4);
}

.mmf02ltsv {
  stop-color: var(--svg-color--cc937c, #CC937C);
}

.mpjri6nek {
  stop-color: var(--svg-color--f5dda4, #F5DDA4);
  stop-opacity: 0;
}

.mx0e40buh {
  d: path("M12.053 2.447c-.529-.116-1.326.468-1.38.664c.978 1.6 1.781 1.577 3.126 1.526c.747-.028.807.238.87.4c.123-2.125-1.41-2.323-2.616-2.59");
}

.mz51gmfzq {
  stop-color: var(--svg-color--e73e59, #E73E59);
  stop-opacity: 0;
}

.n25i9mbre {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.335 7.462a1.4 1.4 0 0 1-.664-.16c-.066-.035-.136.04-.095.102a.902.902 0 0 0 1.518 0c.042-.064-.029-.137-.095-.103a1.4 1.4 0 0 1-.664.161Z");
}

.n4cgu8b4a {
  fill: var(--svg-color--e5ad92, #E5AD92);
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.nk2v8nx5g {
  stop-color: var(--svg-color--f2d3a5, #F2D3A5);
}

.nn0drmzdc {
  d: path("M13.324 5.689c.03.04-.033.088-.103.14s-.123.09-.152.05c-.03-.04.003-.114.074-.167c.07-.052.15-.063.18-.023");
}

.o59cz6b0z {
  d: path("m12.156 5.933l-.248.794a.252.252 0 0 0 .243.327h.368a.253.253 0 0 0 .243-.327l-.248-.794c-.054-.176-.302-.176-.358 0");
}

.o5cnyqbgj {
  d: path("M18.847 8.508h-4.116l.555 2.203h3.508c1.486 0 2.375-1.063 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.155.784-.215a1 1 0 0 0 .508-.343l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.167-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.133.12-.417.448-.492.804a2.8 2.8 0 0 0-.028.758c.013.151.024.303.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.o7mqan3qw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.218 5.473a.65.65 0 0 0-.633.495a.13.13 0 0 0 .125.159h1.042c.067 0 .12-.06.106-.127a.654.654 0 0 0-.64-.527");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.off1fssuq {
  stop-color: var(--svg-color--ce978b, #CE978B);
}

.ok0xogb6i {
  stop-color: var(--svg-color--d39b83, #D39B83);
}

.ols1i2kaq {
  stop-color: var(--svg-color--e9ac8f, #E9AC8F);
}

.otc9m4bci {
  stop-color: var(--svg-color--cc937c, #CC937C);
  stop-opacity: 0;
}

.owmsj2b8b {
  stop-color: var(--svg-color--ddcc9f, #DDCC9F);
  stop-opacity: 0;
}

.p8im66f_y {
  stop-color: var(--svg-color--bb7b77, #BB7B77);
}

.p98xi8b4g {
  stop-color: var(--svg-color--ca9281, #CA9281);
  stop-opacity: 0;
}

.ph4flqb3k {
  stop-color: var(--svg-color--e6b49a, #E6B49A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppa6_abwh {
  stop-color: var(--svg-color--9a3037, #9A3037);
}

.pquvpov8y {
  stop-color: var(--svg-color--fff8ba, #FFF8BA);
}

.pwjuhq5xz {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M12.869 5.836c.124-.218.312-.39.718-.39a.77.77 0 0 1 .5.172c.127.102.11.231.012.28l-.26.148c-.304-.098-.64-.111-.97-.21");
}

.q_d1lub6r {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
  stop-opacity: 0;
}

.q3e93811r {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M12.335 7.462a1.4 1.4 0 0 1-.664-.16c-.066-.035-.136.04-.095.102a.902.902 0 0 0 1.518 0c.042-.064-.029-.137-.095-.103a1.4 1.4 0 0 1-.664.161");
}

.qq2gex10o {
  stop-color: var(--svg-color--c98b81, #C98B81);
  stop-opacity: 0;
}

.qu5j33bza {
  stop-color: var(--svg-color--bf765e, #BF765E);
  stop-opacity: 0;
}

.qyq5h-jrz {
  fill: var(--svg-color--c7887f, #C7887F);
  d: path("m12.152 5.998l-.32.794a.253.253 0 0 0 .244.327h.367a.253.253 0 0 0 .243-.327l-.248-.794c-.053-.176-.23-.176-.286 0");
}

.r38-lhbhs {
  stop-color: var(--svg-color--e9283f, #E9283F);
}

.rau17bcwj {
  stop-color: var(--svg-color--c78a84, #C78A84);
  stop-opacity: 0;
}

.rl7em7bjk {
  stop-color: var(--svg-color--e5c199, #E5C199);
  stop-opacity: 0;
}

.rvjiiobzz {
  stop-color: var(--svg-color--e9ba9b, #E9BA9B);
}

.rxdm1gb4b {
  stop-color: var(--svg-color--6c1118, #6C1118);
}

.ryea0ookf {
  stop-color: var(--svg-color--b77351, #B77351);
}

.s1hry0blp {
  stop-color: var(--svg-color--c5887d, #C5887D);
  stop-opacity: 0;
}

.s2wvo_jzf {
  stop-color: var(--svg-color--f6dbaa, #F6DBAA);
  stop-opacity: 0;
}

.sbhmekbbs {
  d: path("M6.368 12.84c1.433 1.244 3.323.958 4.089.691v-3.65h5.718c.408-1.046.123-1.935-.187-2.42a.22.22 0 0 1-.023-.19c.065-.185.152-.485.164-.722c.024-.52-.136-.558-.152-1.273s-.242-.979-.617-1.59c-.303-.493-1.084-.814-1.56-1.002c-.521-.207-.707-.598-1.494-.598c-.608 0-1.009.308-1.285.575a.67.67 0 0 1-.38.182c-.966.129-1.79.58-2.247 1.422c-.268.494-.291 1.27-.288 1.8a.42.42 0 0 1-.333.406c-1.208.272-2.094.97-2.513 1.761c-.457.863-.683 3.055 1.108 4.609");
}

.shpp5nbho {
  stop-color: var(--svg-color--be7f64, #BE7F64);
}

.st4hs763z {
  stop-color: var(--svg-color--e5c199, #E5C199);
}

.t_3eddbyn {
  d: path("M10.155 6.604a.502.502 0 1 0 0-1.004a.502.502 0 0 0 0 1.004");
}

.t8p_nhwqa {
  fill: var(--svg-color--8c592c, #8C592C);
  fill-rule: evenodd;
  d: path("m14.078 5.058l-.064.107za.125.125 0 0 1-.128.215l-.003-.002l-.01-.005l-.042-.022a1 1 0 0 0-.16-.063a1.06 1.06 0 0 0-.501-.043a.125.125 0 1 1-.044-.246c.24-.043.462 0 .62.05a1.5 1.5 0 0 1 .246.104l.016.008l.004.002z");
}

.t9lx25bgr {
  fill: var(--svg-color--8c592c, #8C592C);
  d: path("m10.748 5.271l-.002.002a.125.125 0 0 1-.129-.215l.002-.002l.005-.002l.015-.008l.054-.028c.046-.022.112-.05.191-.075a1.3 1.3 0 0 1 .621-.051a.125.125 0 0 1-.044.246a1.06 1.06 0 0 0-.5.043a1.3 1.3 0 0 0-.203.085z");
}

.tg25wbqgg {
  cx: 11.188px;
  cy: 5.778px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.181px;
  ry: 0.092px;
}

.tgd5bcc3y {
  stop-color: var(--svg-color--e0a37b, #E0A37B);
  stop-opacity: 0;
}

.u6ezkbbkd {
  stop-color: var(--svg-color--ee3148, #EE3148);
}

.u8l8bnbbx {
  fill: var(--svg-color--ff444f, #FF444F);
  d: path("m19.082 27.535l.571 1.176c.25.586.832 1.172 1.844 1.172h.77a.1.1 0 0 0 .091-.14l-.628-1.444z");
}

.uh_t_cc5j {
  stop-color: var(--svg-color--c98a88, #C98A88);
}

.uh03xc5sy {
  stop-color: var(--svg-color--f0ba9b, #F0BA9B);
}

.uoi807b3e {
  stop-color: var(--svg-color--e9b89b, #E9B89B);
  stop-opacity: 0;
}

.uq-36861a {
  stop-color: var(--svg-color--d89d79, #D89D79);
}

.uwqjkbvol {
  d: path("M15.782 29.914h-8.58c-.823-.182-2.47-.85-2.47-2.06c0-1.514 1.345-2.514 1.25-2.576c-.074-.05 3.025-2.425 4.583-3.606l13.045-5.58c.87-.697 2.796-2.081 3.535-2.037c.738.043 1.021 1.007 1.07 1.483v5.533c0 .921-.304 1.951-.985 2.404c-.68.453-1.212.343-2.26.343c-1.173 0-1.454.336-1.908 1.749c-.363 1.13-.985 1.381-1.9 1.381h-1.189c-.805 0-1.345.172-1.798 1.67c-.4 1.08-1.408 1.296-2.393 1.296");
}

.v3i-1pmwj {
  d: path("M10.92 3.996c-.174.446-.933.812-1.272.901c-.113-.904.237-1.994 1.344-1.798l.187.724c-.187-.053-.226.087-.26.173");
}

.vopejgz3x {
  stop-color: var(--svg-color--bd806d, #BD806D);
}

.vvmjs9bob {
  stop-color: var(--svg-color--a55c3e, #A55C3E);
}

.vzbwqpbmt {
  cx: 11.188px;
  cy: 5.778px;
  rx: 0.181px;
  ry: 0.092px;
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w39yz6l0u {
  stop-color: var(--svg-color--dc2d68, #DC2D68);
}

.w5pmvqbyv {
  stop-color: var(--svg-color--d19d8b, #D19D8B);
}

.wiiznx1ow {
  stop-color: var(--svg-color--ddcc9f, #DDCC9F);
}

.ws5-tkbbq {
  d: path("m13.116 10.256l-1.752-1.6l.383-.172h2.04V9.96a.4.4 0 0 1-.67.296");
}

.wt_le6l3f {
  stop-color: var(--svg-color--bf765e, #BF765E);
}

.wzt3udgik {
  stop-color: var(--svg-color--c9334f, #C9334F);
}

.x_atgxb_v {
  stop-color: var(--svg-color--911c39, #911C39);
}

.xbj9zzvwg {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
  stop-opacity: 0;
}

.xv_mpdbhn {
  stop-color: var(--svg-color--cb8e81, #CB8E81);
  stop-opacity: 0;
}

.y_ccjxb5k {
  stop-color: var(--svg-color--e73950, #E73950);
}

.yiq9sac5t {
  stop-color: var(--svg-color--cf9981, #CF9981);
}

.ynngk8bxm {
  stop-color: var(--svg-color--c5887d, #C5887D);
}

.ynticpbfc {
  d: path("M9.959 5.512h.005l-.004-.124l-.005-.143c.01-.443.268-.615.378-.672l.024-.01l.024-.009c.25-.114.45-.314.556-.577l.038-.09a.123.123 0 0 1 .216-.024c.335.491.896.782 1.49.782h1.504c.084 0 .505.04.53.622l-.055 1.436c-.058 1.309-1.08 2.188-2.328 2.188s-2.27-.88-2.328-2.188z");
}

.ypcbyhbui {
  fill: var(--svg-color--daa587, #DAA587);
  d: path("m12.156 5.933l-.248.794a.252.252 0 0 0 .243.327h.368a.253.253 0 0 0 .243-.327l-.248-.794c-.054-.176-.302-.176-.358 0");
}

.yskuwwbra {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.324 5.689c.03.04-.033.088-.103.14s-.123.09-.152.05c-.03-.04.003-.114.074-.167c.07-.052.15-.063.18-.023");
}

.yu3j8mbni {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
  stop-opacity: 0;
}

.yung1xdgy {
  stop-color: var(--svg-color--851e29, #851E29);
}

.yz2fjsnhb {
  stop-color: var(--svg-color--bb7854, #BB7854);
  stop-opacity: 0;
}

.z1qtb2bfq {
  d: path("M13.726 5.961a.4.4 0 0 0-.108-.215l-.12.133l.054.106z");
}

.zn1rvob2u {
  stop-color: var(--svg-color--dcca95, #DCCA95);
}

.zstr-2b3h {
  stop-color: var(--svg-color--ff3b57, #FF3B57);
}

</style>

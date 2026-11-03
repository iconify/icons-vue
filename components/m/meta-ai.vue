<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255.323,"left":29,"top":15};
const content = `<mask id="SVGCnctOd9O" width="253" height="168" x="63" y="145" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="n0cjo01qp"/></mask><defs><filter id="SVGu98YmeSs" width="426.97" height="334.771" x="-26.255" y="45.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGY6VMHehh" width="526.589" height="399.572" x="-100.749" y="16.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="52.187"/></filter><filter id="SVGNIb6l3yB" width="364.515" height="332.31" x="-43.026" y="81.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVG3D9vaefC" width="364.126" height="277.68" x="9.944" y="113.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGfkheTa3Q" width="331.018" height="281.247" x="-87.361" y="111.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGhRxwPclY" width="293.367" height="259.783" x="-58.09" y="101.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGUsuHcecu" width="328.614" height="180.48" x="39" y="136.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="13.409" dy="-4.789"/><feGaussianBlur stdDeviation="9.578"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.203922 0 0 0 0 1 0 0 0 0.7 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGrGAWjd2S" width="307.487" height="194.716" x="17.016" y="130.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-4.342" dy="-9.582"/><feGaussianBlur stdDeviation="8.35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.257843 0 0 0 0 0.0723032 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGLVv5Od8Q" width="257.703" height="173.507" x="61.799" y="143.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2.045" dy="1.535"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGLhDMLe1G" width="295.081" height="201.245" x="62.817" y="130.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="10"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.207843 0 0 0 0 1 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGVnvmuesE" width="106.911" height="17.462" x="137.068" y="149.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter><filter id="SVGa81cVbiq" width="298.001" height="362.156" x="-16.115" y="279.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="20.875"/></filter><filter id="SVGSdxZTbfo" width="244.182" height="242.416" x="15.334" y="281.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="20.875"/></filter><filter id="SVGdM8RMAam" width="379.768" height="293.958" x="-10.06" y="325.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="52.187"/></filter><filter id="SVGCmrFqcGZ" width="305.903" height="310.831" x="-69.391" y="403.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGFjCsjeGO" width="305.903" height="310.831" x="12.672" y="246.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGmzpY6coF" width="267.318" height="279.394" x="6.313" y="303.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="13.409" dy="-15.228"/><feGaussianBlur stdDeviation="6.262"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.207843 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGKXJzdLBh" width="214.785" height="221.394" x="28.455" y="347.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2.045" dy="-.51"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGD1oP9ugN" width="72.063" height="83.247" x="46.718" y="373.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter><filter id="SVGRNzBXBVg" width="257.256" height="389.2" x="152.031" y="451.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="20.875"/></filter><filter id="SVGlUzMMd5M" width="305.92" height="373.273" x="166.527" y="430.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="52.187"/></filter><filter id="SVG97ax47Bn" width="282.616" height="330.086" x="185.993" y="581.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGB2fujdGC" width="207.824" height="325.559" x="174.857" y="469.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="13.409" dy="-15.228"/><feGaussianBlur stdDeviation="6.262"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.207843 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGOG1qHcdc" width="174.293" height="254.281" x="193.889" y="515.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.025" dy="-1.535"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGNaKcTc0B" width="27.87" height="105.141" x="199.326" y="604.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter><filter id="SVGo4nU6bYq" width="386.337" height="262.201" x="325.159" y="515.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="20.875"/></filter><filter id="SVGw6Jkyd0w" width="314.485" height="367.912" x="362.563" y="414.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="52.187"/></filter><filter id="SVG2WPcMcAQ" width="320.736" height="294.854" x="465.44" y="525.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGZUsEEeOm" width="294.454" height="261.253" x="403.392" y="542.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGdw4pxcPK" width="259.207" height="216.158" x="380.174" y="541.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-5.219" dy="5.219"/><feGaussianBlur stdDeviation="3.131"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.207843 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGnjsP9dFc" width="237.523" height="196.164" x="396.748" y="546.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.51" dy="-2.045"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGOVkeqc0G" width="95.688" height="53.642" x="437.358" y="679.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter><filter id="SVGxhBrzcqR" width="468.47" height="342.93" x="429.969" y="267.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGsAhhHbAt" width="390.889" height="325.144" x="490.441" y="193.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGM7ZV2AlM" width="269.217" height="200.974" x="523.266" y="368.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="5.751" dy="5.647"/><feGaussianBlur stdDeviation="12.525"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.203922 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGGRrl6cCO" width="275.168" height="219.353" x="537.297" y="362.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.211" dy="2.943"/><feGaussianBlur stdDeviation="6.262"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.257843 0 0 0 0 0.0723032 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVG70tARdDB" width="249.636" height="185.673" x="538.146" y="369.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.535" dy="-.51"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGrkkRDe4e" width="98.488" height="47.802" x="643.145" y="500.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter><filter id="SVGRHCUGcrx" width="352.632" height="429.587" x="447.949" y="22.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGtXBkHeiR" width="381.753" height="512.855" x="391.675" y="-110.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGffMdleEa" width="276.22" height="414.882" x="505.848" y="-147.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGYAH0LeBQ" width="241.801" height="327.584" x="489.939" y="108.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="15.324" dy="7.662"/><feGaussianBlur stdDeviation="9.578"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVG3VREqcHI" width="276.149" height="330.337" x="431.703" y="19.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGidtuNbKP" width="186.356" height="257.668" x="522.343" y="104.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="5.747" dy="-4.789"/><feGaussianBlur stdDeviation="9.578"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.203922 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGVwmyPcqb" width="210.572" height="289.845" x="524.225" y="78.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.916" dy="-9.578"/><feGaussianBlur stdDeviation="6.262"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.257843 0 0 0 0 0.0723032 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGc5lvtdEI" width="180.145" height="252.062" x="522.787" y="107.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.28" dy="1.535"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGWZ6yLeqN" width="205.783" height="291.776" x="504.957" y="108.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="10"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.207843 0 0 0 0 1 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVG0GMkBbFb" width="33.402" height="103.7" x="663.006" y="197.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter><filter id="SVGWiCxiTon" width="369.706" height="400.897" x="228.786" y="-83.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGNdn3Ldwp" width="326.649" height="314.435" x="235.611" y="-29.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="23.944"/></filter><filter id="SVGFJIfB0Ys" width="359.822" height="328.66" x="147.196" y="-36.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVG4XEh9cSq" width="300.453" height="297.712" x="292.118" y="-33.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVG1g1zBbhl" width="283.524" height="297.118" x="289.747" y="23.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGM1Nvccuz" width="350.89" height="402.282" x="107.667" y="-190.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGPeXImdMj" width="265.048" height="289.355" x="205.494" y="-93.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="42.38"/></filter><filter id="SVGoMfhMbCN" width="271.53" height="312.238" x="297.492" y="-4.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="15.324" dy="7.662"/><feGaussianBlur stdDeviation="9.578"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGykZnqdeh" width="239.614" height="274.214" x="296.587" y="-.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="13.409" dy="-4.789"/><feGaussianBlur stdDeviation="9.578"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.203922 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGbujt5dKF" width="228.138" height="271.881" x="279.601" y="-20.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.916" dy="-9.578"/><feGaussianBlur stdDeviation="4.175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.257843 0 0 0 0 0.0723032 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGhi4EXVoi" width="202.691" height="232.43" x="300.812" y="13.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".51" dy="2.045"/><feGaussianBlur stdDeviation="1.535"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVGgP8JWd0j" width="233.01" height="270.035" x="297.161" y="12.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="10"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.207843 0 0 0 0 1 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_107_4058"/></filter><filter id="SVG9dQpkebQ" width="67.013" height="87.26" x="422.525" y="43.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_107_4058" stdDeviation="1.915"/></filter></defs><g mask="url(#SVGCnctOd9O)" transform="translate(19.219 10.252)scale(.33836)"><path class="f9_2r4yzl"/><g filter="url(#SVGu98YmeSs)"><ellipse transform="rotate(-86.429 187.23 212.843)" class="nhkh35bmv"/></g><g filter="url(#SVGY6VMHehh)"><ellipse transform="rotate(-95.35 162.546 216.379)" class="qs64lvb8o"/></g><g filter="url(#SVGNIb6l3yB)"><ellipse transform="rotate(-113.206 139.231 248.002)" class="q2wyqyb4n"/></g><g filter="url(#SVG3D9vaefC)"><ellipse transform="rotate(-104.408 192.007 252.648)" class="s5ih9_zdk"/></g><g filter="url(#SVGfkheTa3Q)"><ellipse transform="rotate(-86.429 78.147 251.908)" class="j7aj562di"/></g><g filter="url(#SVGhRxwPclY)"><ellipse transform="rotate(-76.314 88.594 230.906)" class="bj4wu6bnj"/></g><g filter="url(#SVGUsuHcecu)"><path class="fl102bt-z"/></g><g filter="url(#SVGrGAWjd2S)"><path class="nz5ax1-pm"/></g><g filter="url(#SVGLVv5Od8Q)" class="mc2zb0bvp"><path class="crfnwrf6z"/></g><g filter="url(#SVGLhDMLe1G)"><path class="um75wp0_i"/></g><g filter="url(#SVGVnvmuesE)"><path class="t3tx-vs3j"/></g></g><mask id="SVG9DHKaeUb" width="211" height="218" x="29" y="349" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="kw2rkcbmq"/></mask><g mask="url(#SVG9DHKaeUb)" transform="translate(19.219 10.252)scale(.33836)"><path class="hnznn9bzf"/><g filter="url(#SVGa81cVbiq)"><ellipse transform="rotate(-146.838 132.885 460.343)" class="x5dzosbzr"/></g><g filter="url(#SVGSdxZTbfo)"><ellipse transform="rotate(-134.478 137.425 402.884)" class="k41yszbqx"/></g><g filter="url(#SVGdM8RMAam)"><path class="zvpmj4bsw"/></g><g filter="url(#SVGCmrFqcGZ)"><ellipse transform="rotate(-137.857 83.561 559.335)" class="tk3ckxfwu"/></g><g filter="url(#SVGFjCsjeGO)"><ellipse transform="rotate(-137.857 165.624 402.367)" class="w2p-nzbgq"/></g><g filter="url(#SVGmzpY6coF)"><path class="e430x5bfv"/></g><g filter="url(#SVGKXJzdLBh)" class="j3lru8bnq"><path class="c0mydeb5q"/></g><g filter="url(#SVGD1oP9ugN)"><path class="kp6t-xbxi"/></g></g><mask id="SVG5DCcDedE" width="171" height="251" x="194" y="518" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="gthsnndlp"/></mask><g mask="url(#SVG5DCcDedE)" transform="translate(19.219 10.252)scale(.33836)"><path class="viwebnb8w"/><g filter="url(#SVGRNzBXBVg)"><ellipse transform="rotate(161.734 280.659 646.497)" class="zmsowjsma"/></g><g filter="url(#SVGlUzMMd5M)"><path class="w-yvv5buy"/></g><g filter="url(#SVG97ax47Bn)"><ellipse transform="rotate(170.714 327.301 746.78)" class="ffj9djfna"/></g><g filter="url(#SVGB2fujdGC)"><path class="r02dxj90e"/></g><g filter="url(#SVGOG1qHcdc)" class="mc2zb0bvp"><path class="s6makgbsd"/></g><g filter="url(#SVGNaKcTc0B)"><path class="pecdy4b1z"/></g></g><mask id="SVGSng8jYwI" width="235" height="192" x="398" y="550" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="mcohx9bgn"/></mask><g mask="url(#SVGSng8jYwI)" transform="translate(19.219 10.252)scale(.33836)"><path class="tzkbwpyph"/><g filter="url(#SVGo4nU6bYq)"><ellipse transform="rotate(110.305 518.328 647.036)" class="vn6aeq3gl"/></g><g filter="url(#SVGw6Jkyd0w)"><path class="cdlbgpbgl"/></g><g filter="url(#SVG2WPcMcAQ)"><ellipse transform="rotate(119.286 625.809 673.093)" class="qk4lnobmb"/></g><g filter="url(#SVGZUsEEeOm)"><ellipse transform="rotate(119.286 550.619 673.542)" class="i3dy6nbue"/></g><g filter="url(#SVGdw4pxcPK)"><path class="uhdvizamt"/></g><g filter="url(#SVGnjsP9dFc)" class="mc2zb0bvp"><path class="l9i9b0hce"/></g><g filter="url(#SVGOVkeqc0G)"><path class="xs64rkq0o"/></g></g><mask id="SVGN8emaeQR" width="243" height="184" x="542" y="371" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="d4qi4-uxv"/></mask><g mask="url(#SVGN8emaeQR)" transform="translate(19.219 10.252)scale(.33836)"><path class="ptqvrbbrx"/><g filter="url(#SVGxhBrzcqR)"><ellipse transform="rotate(67.857 664.204 439.341)" class="r_0_47rnq"/></g><g filter="url(#SVGsAhhHbAt)"><ellipse transform="rotate(67.528 685.886 356.485)" class="wp37es1km"/></g><g filter="url(#SVGM7ZV2AlM)"><path class="l8j57s6lm"/></g><g filter="url(#SVGGRrl6cCO)"><path class="ydaaecbji"/></g><g filter="url(#SVG70tARdDB)" class="mc2zb0bvp"><path class="u1w06tbsv"/></g><g filter="url(#SVGrkkRDe4e)"><path class="n8cs3s2fw"/></g></g><mask id="SVG1hMNmzGq" width="177" height="247" x="525" y="109" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="fyb2-7b7o"/></mask><g mask="url(#SVG1hMNmzGq)" transform="translate(19.219 10.252)scale(.33836)"><path class="bq4_bvpqh"/><g filter="url(#SVGRHCUGcrx)"><ellipse transform="rotate(16.429 624.265 236.916)" class="e9omgzz5q"/></g><g filter="url(#SVGtXBkHeiR)"><ellipse transform="rotate(-10.349 582.551 146.299)" class="jdmaqvbre"/></g><g filter="url(#SVGffMdleEa)"><ellipse transform="rotate(16.429 643.957 59.593)" class="vcx5e9p8h"/></g><g filter="url(#SVGYAH0LeBQ)" class="ozarfyqlu"><path class="talwx-adt"/></g><g filter="url(#SVG3VREqcHI)"><ellipse transform="rotate(-10.349 569.777 184.841)" class="m-wlsm5bt"/></g><g filter="url(#SVGidtuNbKP)"><path class="praupacel"/></g><g filter="url(#SVGVwmyPcqb)"><path class="ejzrv2bsp"/></g><g filter="url(#SVGc5lvtdEI)" class="mc2zb0bvp"><path class="omawcqbbi"/></g><g filter="url(#SVGWZ6yLeqN)"><path class="evhzf8bdr"/></g><g filter="url(#SVG0GMkBbFb)"><path class="lzwdy5bgt"/></g></g><mask id="SVG8xBNyb7K" width="199" height="228" x="303" y="15" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="r7on7obbf"/></mask><g mask="url(#SVG8xBNyb7K)" transform="translate(19.219 10.252)scale(.33836)"><path class="mei9vb88z"/><g filter="url(#SVGWiCxiTon)"><ellipse transform="rotate(-35 413.639 117.248)" class="d2ruo_bfc"/></g><g filter="url(#SVGNdn3Ldwp)"><ellipse transform="rotate(-48.902 398.935 127.861)" class="ls3_fz-dv"/></g><g filter="url(#SVGFJIfB0Ys)"><ellipse transform="rotate(-61.777 327.107 127.844)" class="xg2y5t6tm"/></g><g filter="url(#SVG4XEh9cSq)"><ellipse transform="rotate(-46.117 442.345 115.111)" class="tezmulbhy"/></g><g filter="url(#SVG1g1zBbhl)"><ellipse transform="rotate(-35 431.508 171.698)" class="q-w4o6etj"/></g><g filter="url(#SVGM1Nvccuz)"><ellipse transform="rotate(-35 283.112 10.658)" class="afebq5bdq"/></g><g filter="url(#SVGPeXImdMj)"><ellipse transform="rotate(-24.886 338.018 51.39)" class="hv2pp-bch"/></g><g filter="url(#SVGoMfhMbCN)" class="ozarfyqlu"><path class="nt8_jacjb"/></g><g filter="url(#SVGykZnqdeh)"><path class="tf0b2bcez"/></g><g filter="url(#SVGbujt5dKF)"><path class="oep1cnb4y"/></g><g filter="url(#SVGhi4EXVoi)" class="mc2zb0bvp"><path class="t7pkcsbmf"/></g><g filter="url(#SVGgP8JWd0j)"><path class="n1lt7711x"/></g><g filter="url(#SVG9dQpkebQ)"><path class="ywqp8hd9c"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:meta-ai" /></template>
<style>
.afebq5bdq {
  cx: 283.112px;
  cy: 10.658px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  rx: 55.741px;
  ry: 136.571px;
}

.bj4wu6bnj {
  cx: 88.594px;
  cy: 230.906px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 43.846px;
  ry: 62.822px;
}

.bq4_bvpqh {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M596 356c-46 0-71-46-71-95c0-66 45-152 107-152c46 0 70 48 70 96c0 64-43 151-106 151");
}

.c0mydeb5q {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M71.338 400.696c47.131-52.082 113.762-68.582 148.825-36.853c35.063 31.73 25.28 99.673-21.851 151.756S84.549 584.181 49.487 552.451c-35.063-31.729-25.28-99.672 21.85-151.755");
}

.cdlbgpbgl {
  fill: var(--svg-color--3235ff, #3235ff);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M487.225 616.027c-22.993-42.869-27.046-85.445-9.052-95.096c17.993-9.65 51.219 17.278 74.212 60.147s27.046 85.445 9.052 95.096c-17.993 9.651-51.219-17.278-74.212-60.147");
}

.crfnwrf6z {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M194.971 143.808c70.536 4.403 125.323 46.301 122.372 93.582s-62.523 82.041-133.058 77.639c-70.536-4.403-125.323-46.301-122.372-93.582s62.523-82.041 133.058-77.639");
}

.d2ruo_bfc {
  cx: 413.639px;
  cy: 117.248px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  rx: 82.389px;
  ry: 128.871px;
}

.d4qi4-uxv {
  d: path("M785 439c0 66-90 116-158 116c-52 0-85-30-85-69c0-64 88-115 158-115c51 0 85 27 85 68");
}

.e430x5bfv {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M62.902 385.186c58.481-64.626 137.591-88.327 176.698-52.938s23.4 116.466-35.082 181.091S66.927 601.665 27.82 566.276s-23.4-116.465 35.082-181.09");
}

.e9omgzz5q {
  cx: 624.265px;
  cy: 236.916px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  rx: 86.987px;
  ry: 133.095px;
}

.ejzrv2bsp {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M724.688 256.366c-22.343 75.778-83.498 124.517-136.592 108.862s-78.022-89.776-55.678-165.554S615.916 75.157 669.01 90.812s78.022 89.776 55.678 165.554");
}

.evhzf8bdr {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M701.916 280.345c-22.99 77.962-83.742 128.742-135.693 113.423c-51.952-15.32-75.431-90.939-52.441-168.9s83.741-128.743 135.693-113.423s75.43 90.939 52.441 168.9");
}

.f9_2r4yzl {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M197 313c-66 0-134-36-134-88c0-48 57-80 119-80c66 0 134 36 134 89c0 50-60 79-119 79");
}

.ffj9djfna {
  cx: 327.301px;
  cy: 746.78px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  rx: 55.741px;
  ry: 80.83px;
}

.fl102bt-z {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M202.051 141.923c86.988 5.43 155.067 48.91 152.058 97.117c-3.008 48.207-75.966 82.885-162.954 77.456s-155.067-48.91-152.059-97.117c3.01-48.207 75.966-82.885 162.955-77.456");
}

.fyb2-7b7o {
  d: path("M596 356c-46 0-71-46-71-95c0-66 45-152 107-152c46 0 70 48 70 96c0 64-43 151-106 151");
}

.gthsnndlp {
  d: path("M365 660c0 52-27 109-75 109c-56 0-96-78-96-143c0-53 27-108 75-108c58 0 96 81 96 142");
}

.hnznn9bzf {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M95 567c-40 0-66-27-66-68c0-70 76-150 146-150c41 0 65 27 65 67c0 72-76 151-145 151");
}

.hv2pp-bch {
  cx: 338.018px;
  cy: 51.391px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  rx: 43.846px;
  ry: 62.822px;
}

.i3dy6nbue {
  cx: 550.619px;
  cy: 673.542px;
  fill: var(--svg-color--3235ff, #3235ff);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 35.769px;
  ry: 68.735px;
}

.j3lru8bnq {
  opacity: var(--svg-opacity--0-25, 0.25);
}

.j7aj562di {
  cx: 78.147px;
  cy: 251.908px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 55.741px;
  ry: 80.83px;
}

.jdmaqvbre {
  cx: 582.551px;
  cy: 146.299px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  rx: 103.085px;
  ry: 173.473px;
}

.k41yszbqx {
  cx: 137.425px;
  cy: 402.884px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  rx: 50.151px;
  ry: 101.23px;
}

.kp6t-xbxi {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M50.548 452.754c6.898-18.342 18.98-36.951 35.698-53.265c9.064-8.845 18.769-16.311 28.705-22.322c-8.227 5.934-16.314 12.709-24.073 20.281c-17.786 17.357-31.437 36.531-40.33 55.306");
}

.kw2rkcbmq {
  d: path("M95 567c-40 0-66-27-66-68c0-70 76-150 146-150c41 0 65 27 65 67c0 72-76 151-145 151");
}

.l8j57s6lm {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M688.681 548.81c-70.317 28.615-142.4 14.752-161.003-30.962s23.321-105.968 93.638-134.583s142.401-14.752 161.003 30.963c18.603 45.714-23.32 105.968-93.638 134.582");
}

.l9i9b0hce {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M473.965 719.97c-61.224-34.337-92.141-95.54-69.056-136.702s91.431-46.693 152.655-12.356c61.223 34.337 92.141 95.54 69.055 136.702s-91.431 46.693-152.654 12.356");
}

.ls3_fz-dv {
  cx: 398.935px;
  cy: 127.861px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 87.138px;
  ry: 132.965px;
}

.lzwdy5bgt {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M692.084 200.887c1.739 19.519-1.077 41.527-9.065 63.478c-4.331 11.901-9.838 22.837-16.184 32.562c4.84-8.915 9.188-18.527 12.896-28.715c8.498-23.353 12.482-46.55 12.353-67.325");
}

.m-wlsm5bt {
  cx: 569.777px;
  cy: 184.841px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  rx: 52.115px;
  ry: 81.175px;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mcohx9bgn {
  d: path("M553 742c-71 0-155-62-155-128c0-43 36-64 78-64c72 0 157 63 157 127c0 42-37 65-80 65");
}

.mei9vb88z {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M502 172c0 41-22 71-63 71c-69 0-136-86-136-156c0-40 22-72 64-72c69 0 135 86 135 157");
}

.n0cjo01qp {
  d: path("M197 313c-66 0-134-36-134-88c0-48 57-80 119-80c66 0 134 36 134 89c0 50-60 79-119 79");
}

.n1lt7711x {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M494.002 89.503c46.6 66.552 48.409 145.688 4.041 176.755s-118.112 2.301-164.713-64.251s-48.409-145.688-4.041-176.755s118.112-2.3 164.713 64.251");
}

.n8cs3s2fw {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M737.803 504.171c-14.176 13.53-33.138 25.051-55.28 32.492c-12.004 4.034-23.989 6.548-35.548 7.65c9.987-1.775 20.213-4.369 30.49-7.822c23.556-7.917 44.177-19.266 60.338-32.32");
}

.nhkh35bmv {
  cx: 187.23px;
  cy: 212.843px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  rx: 82.389px;
  ry: 128.871px;
}

.nt8_jacjb {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M507.088 90.653c54.585 77.955 62.349 166.698 17.341 198.212c-45.007 31.515-125.743-6.132-180.327-84.087S281.753 38.08 326.761 6.565s125.743 6.133 180.327 84.088");
}

.nz5ax1-pm {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M178.678 140.097c83.65 5.221 148.889 50.677 145.715 101.529s-73.559 87.844-157.209 82.623S18.296 273.572 21.47 222.72c3.173-50.853 73.558-87.844 157.208-82.623");
}

.oep1cnb4y {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M467.825 67.072c46.706 66.703 50.94 144.324 9.456 173.372c-41.484 29.047-112.977-1.479-159.683-68.182S266.659 27.937 308.143-1.111C349.627-30.158 421.119.37 467.825 67.072");
}

.omawcqbbi {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M695.238 257.101c-20.014 67.875-72.833 112.109-117.976 98.798s-65.513-79.125-45.5-147s72.833-112.109 117.976-98.798s65.513 79.125 45.5 147");
}

.ozarfyqlu {
  opacity: var(--svg-opacity--0-7, 0.7);
}

.pecdy4b1z {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M223.366 706.131c-10.038-16.83-17.053-37.879-19.384-61.121c-1.263-12.602-1.049-24.845.448-36.36c-.491 10.132-.236 20.679.845 31.466c2.479 24.727 8.959 47.355 18.091 66.015");
}

.praupacel {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M695.188 259.621c-20.201 68.511-73.532 113.154-119.118 99.713s-66.164-79.877-45.963-148.388s73.532-113.155 119.118-99.713c45.586 13.441 66.164 79.877 45.963 148.388");
}

.ptqvrbbrx {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M785 439c0 66-90 116-158 116c-52 0-85-30-85-69c0-64 88-115 158-115c51 0 85 27 85 68");
}

.q-w4o6etj {
  cx: 431.508px;
  cy: 171.698px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  rx: 49.61px;
  ry: 69.689px;
}

.q2wyqyb4n {
  cx: 139.231px;
  cy: 248.002px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 77.296px;
  ry: 100.741px;
}

.qk4lnobmb {
  cx: 625.809px;
  cy: 673.093px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  rx: 55.741px;
  ry: 80.83px;
}

.qs64lvb8o {
  cx: 162.546px;
  cy: 216.379px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 94.645px;
  ry: 159.365px;
}

.r_0_47rnq {
  cx: 664.204px;
  cy: 439.341px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  rx: 67.655px;
  ry: 158.985px;
}

.r02dxj90e {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M178.262 654.355c-14.064-86.016 16.73-162.644 68.781-171.154c52.05-8.511 105.646 54.32 119.709 140.335s-16.73 162.644-68.781 171.155c-52.05 8.51-105.646-54.321-119.709-140.336");
}

.r7on7obbf {
  d: path("M502 172c0 41-22 71-63 71c-69 0-136-86-136-156c0-40 22-72 64-72c69 0 135 86 135 157");
}

.s5ih9_zdk {
  cx: 192.007px;
  cy: 252.648px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  rx: 49.61px;
  ry: 99.64px;
}

.s6makgbsd {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M196.379 657.403c-11.342-69.373 17.135-131.77 63.606-139.368s93.338 42.481 104.681 111.854c11.342 69.372-17.135 131.77-63.606 139.368s-93.338-42.481-104.681-111.854");
}

.t3tx-vs3j {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M140.898 159.636c18.642-6.041 40.724-8.197 63.902-5.298c12.567 1.572 24.455 4.505 35.349 8.526c-9.769-2.733-20.108-4.831-30.865-6.177c-24.66-3.085-48.162-1.803-68.386 2.949");
}

.t7pkcsbmf {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M471.849 79.964c40.308 57.565 41.667 126.159 3.036 153.209s-102.623 2.311-142.931-55.254c-40.307-57.566-41.667-126.16-3.036-153.21C367.549-2.34 431.541 22.4 471.849 79.965");
}

.talwx-adt {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M706.49 298.925c-25.567 86.71-92.548 143.365-149.606 126.541S474.298 324.71 499.865 238c25.568-86.711 92.549-143.365 149.607-126.541s82.585 100.755 57.018 187.466");
}

.tezmulbhy {
  cx: 442.345px;
  cy: 115.111px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 43.846px;
  ry: 80.427px;
}

.tf0b2bcez {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M481.329 88.902c48.334 69.028 55.442 147.445 15.877 175.149c-39.566 27.704-110.822-5.796-159.156-74.824S282.607 41.782 322.173 14.078s110.822 5.796 159.156 74.824");
}

.tk3ckxfwu {
  cx: 83.561px;
  cy: 559.335px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  rx: 55.741px;
  ry: 80.83px;
}

.tzkbwpyph {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M553 742c-71 0-155-62-155-128c0-43 36-64 78-64c72 0 157 63 157 127c0 42-37 65-80 65");
}

.u1w06tbsv {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M695.751 541.37c-66.172 26.928-134.151 13.527-151.835-29.931c-17.685-43.459 21.622-100.517 87.794-127.445s134.151-13.526 151.836 29.932c17.684 43.458-21.623 100.517-87.795 127.444");
}

.uhdvizamt {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M466.419 729.22c-65.361-36.657-97.766-103.069-72.378-148.335c25.387-45.266 98.953-52.245 164.313-15.588c65.361 36.658 97.766 103.07 72.378 148.336c-25.387 45.266-98.952 52.244-164.313 15.587");
}

.um75wp0_i {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M216.486 131.087c81.413 5.081 144.667 53.16 141.283 107.386s-72.126 94.067-153.539 88.986s-144.667-53.16-141.282-107.387c3.384-54.226 72.126-94.066 153.538-88.985");
}

.vcx5e9p8h {
  cx: 643.957px;
  cy: 59.593px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 41.04px;
  ry: 127.32px;
}

.viwebnb8w {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M365 660c0 52-27 109-75 109c-56 0-96-78-96-143c0-53 27-108 75-108c58 0 96 81 96 142");
}

.vn6aeq3gl {
  cx: 518.328px;
  cy: 647.036px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  fill-opacity: var(--svg-fill-opacity--0-62, 0.62);
  rx: 74.923px;
  ry: 159.026px;
}

.w-yvv5buy {
  fill: var(--svg-color--3235ff, #3235ff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M285.511 602.848c19.18-44.705 49.941-74.419 68.705-66.368s18.426 50.817-.754 95.522c-19.181 44.705-49.941 74.42-68.705 66.369s-18.427-50.818.754-95.523");
}

.w2p-nzbgq {
  cx: 165.624px;
  cy: 402.367px;
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  rx: 55.741px;
  ry: 80.83px;
}

.wp37es1km {
  cx: 685.886px;
  cy: 356.485px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 69.105px;
  ry: 116.291px;
}

.x5dzosbzr {
  cx: 132.885px;
  cy: 460.343px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  rx: 74.923px;
  ry: 159.026px;
}

.xg2y5t6tm {
  cx: 327.107px;
  cy: 127.844px;
  fill: var(--svg-color--ec35ff, #ec35ff);
  rx: 72.325px;
  ry: 100.741px;
}

.xs64rkq0o {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M529.217 729.015c-19.42-2.645-40.254-10.287-59.882-22.961c-10.639-6.869-20.077-14.671-28.146-23.021c7.615 6.701 16.02 13.079 25.127 18.96c20.882 13.483 42.615 22.528 62.901 27.022");
}

.ydaaecbji {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-01, 0.01);
  d: path("M713.749 564.673c-72.619 29.551-148.62 11.409-169.752-40.521s20.607-117.984 93.227-147.535c72.619-29.551 148.62-11.409 169.752 40.521c21.131 51.93-20.607 117.984-93.227 147.535");
}

.ywqp8hd9c {
  fill: var(--svg-color--f277ff, #f277ff);
  d: path("M426.355 47.526c16.347 10.808 31.801 26.73 43.986 46.66c6.603 10.801 11.72 21.92 15.368 32.941c-3.953-9.338-8.757-18.727-14.41-27.973c-12.963-21.203-28.619-38.779-44.944-51.628");
}

.zmsowjsma {
  cx: 280.659px;
  cy: 646.497px;
  fill: var(--svg-color--aa63ff, #aa63ff);
  fill-opacity: var(--svg-fill-opacity--0-62, 0.62);
  rx: 74.923px;
  ry: 159.026px;
}

.zvpmj4bsw {
  fill: var(--svg-color--3235ff, #3235ff);
  d: path("M170.037 436.922c46.911-12.877 89.321-7.355 94.726 12.335s-28.242 46.091-75.153 58.968s-89.321 7.355-94.726-12.335s28.242-46.091 75.153-58.968");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3o4bublz.css';
import '../../css/f/f-a1o0b_o.css';
import '../../css/h/hu0jjp25c.css';
import '../../css/h/hywfbs4sg.css';
import '../../css/u/uahwao0ct.css';
import '../../css/m/m99gr1aku.css';
import '../../css/w/wr4a4yb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t3o4bublz"/><path class="f-a1o0b_o"/><path class="hu0jjp25c"/><path class="hywfbs4sg"/><path class="uahwao0ct"/><path class="m99gr1aku"/><path class="wr4a4yb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nimble" /></template>

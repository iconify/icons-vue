<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaspbr6si.css';
import '../../css/f/f6jk9u_pw.css';
import '../../css/j/j813l0n6f.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/cczuxwb0a.css';
import '../../css/j/jk5rd7bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zaspbr6si"/><path class="f6jk9u_pw"/><path class="j813l0n6f"/><g class="d2kvgvbvc"><path class="cczuxwb0a"/><path class="jk5rd7bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nuxtjs-wordmark" /></template>

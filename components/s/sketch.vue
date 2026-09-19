<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi31eib1s.css';
import '../../css/a/a5notdz6b.css';
import '../../css/g/gh65jv65k.css';
import '../../css/i/iitbkh92y.css';
import '../../css/v/vn9r7dcbi.css';
import '../../css/j/jvcf3m1mi.css';
import '../../css/m/mxj57qx3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hi31eib1s"/><path class="a5notdz6b"/><path class="gh65jv65k"/><path class="iitbkh92y"/><path class="vn9r7dcbi"/><path class="jvcf3m1mi"/><path class="mxj57qx3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sketch" /></template>

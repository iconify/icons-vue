<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b3om0ubnr.css';
import '../../css/z/ztw77h30a.css';
import '../../css/k/k9g2oxbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3om0ubnr"/><path class="ztw77h30a"/><path class="k9g2oxbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:root-third-bracket" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ive95xbok.css';
import '../../css/a/a5lh8nbos.css';
import '../../css/a/ak7k5s97a.css';
import '../../css/w/wzzmmnqec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":79,"height":78};
const content = `<g class="bi12bsetm"><path class="ive95xbok"/><path class="a5lh8nbos"/><path class="ak7k5s97a"/><path class="wzzmmnqec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:postcss" /></template>

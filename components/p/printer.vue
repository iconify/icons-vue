<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b7-l3ptxy.css';
import '../../css/b/bd2-kmgzj.css';
import '../../css/t/t8h1t8byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7-l3ptxy"/><path class="bd2-kmgzj"/><path class="t8h1t8byf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:printer" /></template>

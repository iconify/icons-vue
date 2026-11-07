<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ybmmfzrcm.css';
import '../../css/u/u7mrcgb5f.css';
import '../../css/b/bi0yyqbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ybmmfzrcm"/><path class="u7mrcgb5f"/><path class="bi0yyqbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-navigation-line-duotone" /></template>

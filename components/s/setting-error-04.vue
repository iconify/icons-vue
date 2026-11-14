<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b48nsibwb.css';
import '../../css/j/jqgwa20rl.css';
import '../../css/s/s8h64qb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b48nsibwb"/><path class="jqgwa20rl"/><path class="s8h64qb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:setting-error-04" /></template>

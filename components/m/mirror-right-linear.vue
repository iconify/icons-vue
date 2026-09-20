<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x3dy2qmlr.css';
import '../../css/j/jn20mc0cj.css';
import '../../css/c/cipdabcte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x3dy2qmlr"/><path class="jn20mc0cj"/><path class="cipdabcte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-right-linear" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ov13xzbwz.css';
import '../../css/j/jh6mgrb4y.css';
import '../../css/c/cipdabcte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ov13xzbwz"/><path class="jh6mgrb4y"/><path class="cipdabcte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-right-line-duotone" /></template>

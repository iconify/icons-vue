<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9-r9rubz.css';
import '../../css/e/e451rm0tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9-r9rubz"/><path class="e451rm0tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pie-chart-alt" /></template>

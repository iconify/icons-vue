<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew-ng2h3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew-ng2h3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:medibang-paint" /></template>

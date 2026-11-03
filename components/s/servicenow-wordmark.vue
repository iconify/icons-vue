<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3au-5bor.css';
import '../../css/a/avg_k22jv.css';
import '../../css/i/ic5amcb4z.css';
import '../../css/d/d2wq1dhwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l3au-5bor"/><path class="avg_k22jv"/><path class="ic5amcb4z"/><path class="d2wq1dhwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:servicenow-wordmark" /></template>

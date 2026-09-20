<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdco8y64r.css';
import '../../css/t/ttpvcybxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdco8y64r"/><path class="ttpvcybxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pie-chart-duotone" /></template>

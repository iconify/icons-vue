<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgcdo-zfb.css';
import '../../css/u/ufos4gbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgcdo-zfb"/><path class="ufos4gbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ph-intercept-dark" /></template>

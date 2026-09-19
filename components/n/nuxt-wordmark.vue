<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwf_b-maa.css';
import '../../css/i/iu0_yp7rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gwf_b-maa"/><path class="iu0_yp7rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nuxt-wordmark" /></template>

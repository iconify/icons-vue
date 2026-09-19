<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urc4_cblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="urc4_cblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opera-wordmark" /></template>

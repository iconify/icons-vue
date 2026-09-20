<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm2x4mzsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm2x4mzsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:perplexity-line" /></template>

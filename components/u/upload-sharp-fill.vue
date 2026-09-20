<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apgp81bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apgp81bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:upload-sharp-fill" /></template>

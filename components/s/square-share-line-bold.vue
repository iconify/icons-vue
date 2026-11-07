<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldr9qjosp.css';
import '../../css/p/pdyp1acvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldr9qjosp"/><path clip-rule="evenodd" class="pdyp1acvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-share-line-bold" /></template>

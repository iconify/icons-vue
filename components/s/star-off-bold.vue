<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ax0lebc.css';
import '../../css/n/nyn0a-12z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ax0lebc"/><path class="nyn0a-12z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-off-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueh3k2czz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueh3k2czz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:track-next" /></template>

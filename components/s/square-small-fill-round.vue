<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klo0mm2kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klo0mm2kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-small-fill-round" /></template>

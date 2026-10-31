<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_b7j0aqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_b7j0aqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:running-fill-round" /></template>

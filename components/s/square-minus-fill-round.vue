<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3tc0ffci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3tc0ffci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-minus-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzo5umr7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzo5umr7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-round" /></template>

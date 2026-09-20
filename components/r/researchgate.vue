<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etmml3bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etmml3bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:researchgate" /></template>

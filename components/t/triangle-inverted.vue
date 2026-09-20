<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvll163ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvll163ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-inverted" /></template>

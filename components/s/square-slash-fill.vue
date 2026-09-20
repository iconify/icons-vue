<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8naik3nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8naik3nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-slash-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuwdo-fuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuwdo-fuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:minus-circle" /></template>

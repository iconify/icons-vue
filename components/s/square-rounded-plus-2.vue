<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c76d4sb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c76d4sb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-plus-2" /></template>

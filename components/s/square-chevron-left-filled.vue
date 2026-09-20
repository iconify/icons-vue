<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmlm6xvuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmlm6xvuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-chevron-left-filled" /></template>

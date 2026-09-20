<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey756c4jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey756c4jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-7-filled" /></template>

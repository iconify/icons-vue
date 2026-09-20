<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6kq_-bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6kq_-bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-5-filled" /></template>

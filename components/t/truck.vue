<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsir6wkji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsir6wkji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:truck" /></template>

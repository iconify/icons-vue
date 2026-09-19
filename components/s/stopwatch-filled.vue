<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kykar5ibp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kykar5ibp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stopwatch-filled" /></template>

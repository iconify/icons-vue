<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko-aknbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko-aknbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-minus" /></template>

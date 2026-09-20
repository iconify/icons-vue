<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrsr8rlmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrsr8rlmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-f1-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkmy43dwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkmy43dwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-horizontal-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqq2g7g9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqq2g7g9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal" /></template>

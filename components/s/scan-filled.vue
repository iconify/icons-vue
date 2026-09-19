<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj0_tcbbp.css';
import '../../css/j/jz4jx24-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0_tcbbp"/><path class="jz4jx24-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scan-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4w5a7bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4w5a7bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-off-gloss" /></template>

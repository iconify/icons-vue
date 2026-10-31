<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2xzm_b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2xzm_b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-alt-duocolor-round" /></template>

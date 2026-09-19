<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krfhnqk_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krfhnqk_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:solar-battery" /></template>

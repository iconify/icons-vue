<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knuwu50tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knuwu50tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-search" /></template>

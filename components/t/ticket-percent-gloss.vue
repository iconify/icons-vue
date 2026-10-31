<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3l1uf5yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3l1uf5yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ticket-percent-gloss" /></template>

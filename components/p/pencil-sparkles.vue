<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xan9nxodn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b xan9nxodn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-sparkles" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm-9bbu2i.css';
import '../../css/w/wqk418y-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm-9bbu2i"/><path class="wqk418y-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ticket" /></template>

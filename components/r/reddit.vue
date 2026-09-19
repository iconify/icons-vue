<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soso3u_zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="soso3u_zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:reddit" /></template>

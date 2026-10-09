<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is7w60blm.css';
import '../../css/s/sb8adabhc.css';
import '../../css/u/u9pq35-6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="is7w60blm"/><path class="sb8adabhc"/><path class="u9pq35-6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-plus-20-bold" /></template>

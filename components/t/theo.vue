<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5sthicge.css';
import '../../css/g/gr9tg1wsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5sthicge"/><path class="gr9tg1wsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:theo" /></template>

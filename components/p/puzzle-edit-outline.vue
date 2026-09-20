<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utdbd58xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utdbd58xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-edit-outline" /></template>

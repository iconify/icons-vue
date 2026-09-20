<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvwq-gb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvwq-gb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-time-descending" /></template>

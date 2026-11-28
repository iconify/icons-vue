<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glh1rubhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glh1rubhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-search" /></template>

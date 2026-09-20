<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg9h2sbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg9h2sbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:virus-off" /></template>

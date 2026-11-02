<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrt6ifbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrt6ifbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-3-fill" /></template>

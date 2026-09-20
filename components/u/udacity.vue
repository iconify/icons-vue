<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj930lbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj930lbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:udacity" /></template>

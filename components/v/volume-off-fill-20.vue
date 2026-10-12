<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id0t_9blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="id0t_9blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-off-fill-20" /></template>

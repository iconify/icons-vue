<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3muvh5zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t3muvh5zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:paperclip" /></template>

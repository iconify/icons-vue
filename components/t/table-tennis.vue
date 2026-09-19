<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqj5beb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqj5beb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-tennis" /></template>

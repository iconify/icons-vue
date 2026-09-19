<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqb9p_p2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqb9p_p2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/havq_zbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="havq_zbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plus" /></template>

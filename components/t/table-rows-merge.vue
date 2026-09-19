<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7t4c_ylw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7t4c_ylw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-rows-merge" /></template>

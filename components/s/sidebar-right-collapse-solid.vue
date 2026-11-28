<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi83habxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi83habxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sidebar-right-collapse-solid" /></template>

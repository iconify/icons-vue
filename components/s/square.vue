<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3qgr33im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3qgr33im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square" /></template>

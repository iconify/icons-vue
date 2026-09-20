<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6k5uxbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6k5uxbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-cellular-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqt3ewbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqt3ewbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ship-fill" /></template>

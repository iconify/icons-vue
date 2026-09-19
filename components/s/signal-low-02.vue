<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmbi7nb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmbi7nb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-low-02" /></template>

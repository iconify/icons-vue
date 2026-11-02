<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swlt6vbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swlt6vbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:traffic-cone-fill" /></template>

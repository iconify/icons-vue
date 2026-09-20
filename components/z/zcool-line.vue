<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2qks4blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2qks4blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:zcool-line" /></template>

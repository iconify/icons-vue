<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxfz19a0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxfz19a0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-off" /></template>

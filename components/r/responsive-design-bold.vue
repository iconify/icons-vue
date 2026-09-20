<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq--7gh0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq--7gh0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:responsive-design-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muv-rs82u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muv-rs82u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:warehouse-storage-2-bold" /></template>

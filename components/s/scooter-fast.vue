<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgip4db9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgip4db9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:scooter-fast" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4o03q_zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4o03q_zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:speaker-x-mark-solid" /></template>

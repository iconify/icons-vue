<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze_6td4qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_6td4qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:queue-list" /></template>

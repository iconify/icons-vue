<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfj-dcbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfj-dcbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-powerpoint" /></template>

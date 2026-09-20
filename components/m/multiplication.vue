<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzf3jntxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzf3jntxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:multiplication" /></template>

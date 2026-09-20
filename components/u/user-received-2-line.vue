<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeuan0b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeuan0b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-received-2-line" /></template>

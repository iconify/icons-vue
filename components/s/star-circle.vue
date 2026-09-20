<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tis7hb_9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tis7hb_9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-circle" /></template>

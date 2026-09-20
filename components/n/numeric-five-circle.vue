<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdkry4kfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdkry4kfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-five-circle" /></template>

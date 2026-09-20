<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjz0ovbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjz0ovbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:moon-full" /></template>

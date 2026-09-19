<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uarocz_at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uarocz_at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wifi-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azae8fb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azae8fb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:open-in-new" /></template>

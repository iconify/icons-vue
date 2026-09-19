<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq6uakg9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq6uakg9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:speaker-x-mark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of36-uh_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of36-uh_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-square-heart" /></template>

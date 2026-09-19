<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vamp-db2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vamp-db2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:send-euros" /></template>

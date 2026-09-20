<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl8nwac8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl8nwac8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:server-connection" /></template>

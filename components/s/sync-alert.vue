<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaor40bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaor40bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sync-alert" /></template>

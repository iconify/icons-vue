<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li1hz3b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li1hz3b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection" /></template>

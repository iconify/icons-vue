<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnwn6gu-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnwn6gu-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:valve-open" /></template>

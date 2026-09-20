<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftewb93xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftewb93xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings-pause-outline" /></template>

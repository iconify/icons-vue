<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgod01b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgod01b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:whistle" /></template>

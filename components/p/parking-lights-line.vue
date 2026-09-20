<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm7h6xalq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm7h6xalq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parking-lights-line" /></template>

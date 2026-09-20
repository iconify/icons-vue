<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dun5x8ubx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dun5x8ubx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-cancel" /></template>

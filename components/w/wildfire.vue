<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0t0uybxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0t0uybxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wildfire" /></template>

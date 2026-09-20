<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsonpbh5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsonpbh5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:screenshot-2-line" /></template>

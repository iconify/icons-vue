<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3cuukbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3cuukbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-love" /></template>

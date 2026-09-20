<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v61ltsp8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v61ltsp8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reactjs-fill" /></template>

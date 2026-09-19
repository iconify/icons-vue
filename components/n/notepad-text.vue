<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slf8enbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slf8enbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notepad-text" /></template>

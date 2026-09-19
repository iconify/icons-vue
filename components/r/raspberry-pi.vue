<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek80r3bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="ek80r3bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:raspberry-pi" /></template>

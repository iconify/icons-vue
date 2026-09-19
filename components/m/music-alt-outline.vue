<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwmjj80ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmjj80ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:music-alt-outline" /></template>

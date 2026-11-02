<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4hid8bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4hid8bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:weightlifting-fill" /></template>

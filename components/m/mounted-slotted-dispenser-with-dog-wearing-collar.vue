<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl_5fob-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wl_5fob-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mounted-slotted-dispenser-with-dog-wearing-collar" /></template>

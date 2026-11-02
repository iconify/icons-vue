<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2gs35byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w2gs35byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-gabled-shelter" /></template>

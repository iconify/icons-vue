<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4hgy2b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n4hgy2b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-unmuted-stroke-12" /></template>

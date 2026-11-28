<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swoj7zb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swoj7zb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:washing-machine-play" /></template>

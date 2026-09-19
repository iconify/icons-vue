<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4iq4dbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4iq4dbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-washer" /></template>

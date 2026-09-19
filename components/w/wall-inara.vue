<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wakedjb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wakedjb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-inara" /></template>

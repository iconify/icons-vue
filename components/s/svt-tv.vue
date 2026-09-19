<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rknujcbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rknujcbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:svt-tv" /></template>

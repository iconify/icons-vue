<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwcd64bwj.css';
import '../../css/v/vezww5hdy.css';
import '../../css/i/ipwmjm2oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwcd64bwj"/><path class="vezww5hdy"/><path class="ipwmjm2oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pro-solid" /></template>

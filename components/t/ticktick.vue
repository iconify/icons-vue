<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwva-4bto.css';
import '../../css/e/e84spf9xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwva-4bto"/><path class="e84spf9xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticktick" /></template>

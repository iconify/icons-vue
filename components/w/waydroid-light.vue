<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noywb7vvo.css';
import '../../css/o/obfu5obql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="noywb7vvo"/><path class="obfu5obql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:waydroid-light" /></template>

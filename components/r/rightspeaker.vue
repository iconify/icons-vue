<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj-p7ldds.css';
import '../../css/o/o67rmiljq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sj-p7ldds"/><path class="o67rmiljq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:rightspeaker" /></template>

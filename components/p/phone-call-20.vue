<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz7zambhg.css';
import '../../css/y/yt3jrachk.css';
import '../../css/q/qzi560ajg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tz7zambhg"/><path class="yt3jrachk"/><path class="qzi560ajg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-call-20" /></template>

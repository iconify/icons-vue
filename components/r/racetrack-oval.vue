<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy0hk4bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hy0hk4bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:racetrack-oval" /></template>

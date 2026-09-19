<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn4ka_0ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="yn4ka_0ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:microphone" /></template>

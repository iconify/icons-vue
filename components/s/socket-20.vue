<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmjqnac7l.css';
import '../../css/w/w4wlpvbuu.css';
import '../../css/i/i31k85bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmjqnac7l"/><path class="w4wlpvbuu"/><path class="i31k85bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:socket-20" /></template>

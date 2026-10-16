<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl75yhb6l.css';
import '../../css/u/uqpad_ykf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tl75yhb6l"/><path class="uqpad_ykf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workflow-20" /></template>

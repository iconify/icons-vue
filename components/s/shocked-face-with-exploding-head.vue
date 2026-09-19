<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaus4hbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eaus4hbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shocked-face-with-exploding-head" /></template>

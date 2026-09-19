<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6kie6zvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6kie6zvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:window-maximize" /></template>

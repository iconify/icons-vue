<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr26pabwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nr26pabwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:propellor" /></template>

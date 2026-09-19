<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj213obes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mj213obes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:test-tube" /></template>

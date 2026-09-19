<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj0cu-bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="aj0cu-bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:three-button-mouse" /></template>

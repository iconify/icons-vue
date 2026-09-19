<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ujr3bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f4ujr3bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:roasted-sweet-potato" /></template>

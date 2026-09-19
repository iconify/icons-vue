<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne34-2bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ne34-2bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni54c8-box" /></template>

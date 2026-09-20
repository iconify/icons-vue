<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6y99-9zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y6y99-9zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-on-escalator" /></template>

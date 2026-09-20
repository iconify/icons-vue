<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opvmueyea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="opvmueyea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:scooter-11" /></template>

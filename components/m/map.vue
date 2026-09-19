<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnapf6o7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mnapf6o7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:map" /></template>

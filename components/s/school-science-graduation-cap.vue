<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph7wbnb1k.css';
import '../../css/o/oxriyzb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ph7wbnb1k"/><path class="oxriyzb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:school-science-graduation-cap" /></template>

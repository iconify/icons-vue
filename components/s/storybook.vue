<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbuh8hbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gbuh8hbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:storybook" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqocp9bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="uqocp9bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:speakap" /></template>

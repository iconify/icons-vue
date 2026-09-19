<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-iz-12dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-iz-12dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:plug-and-socket" /></template>

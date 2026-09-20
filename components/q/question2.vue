<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2qtsccxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2qtsccxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:question2" /></template>

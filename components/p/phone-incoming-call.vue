<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-t_xccjl.css';
import '../../css/o/o2jt7mbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-t_xccjl"/><path class="o2jt7mbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:phone-incoming-call" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdz6p2bks.css';
import '../../css/c/c8s5nepqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdz6p2bks"/><path class="c8s5nepqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:respirator-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re0n-jb1b.css';
import '../../css/g/g55m-ob4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="re0n-jb1b"/><path class="g55m-ob4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ppa-20" /></template>

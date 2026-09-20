<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzm4hubxj.css';
import '../../css/p/px297bcje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xzm4hubxj"/><path class="px297bcje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:store" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we_6prbbh.css';
import '../../css/c/ck8dpqbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="we_6prbbh"/><path clip-rule="evenodd" class="ck8dpqbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:question-12" /></template>

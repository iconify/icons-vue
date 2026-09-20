<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8jixq.css';
import '../../css/q/qq3t6k.css';
import '../../css/d/d-45nhxp.css';
import '../../css/r/r-from-0px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8jixq"/><circle class="qq3t6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:watch" /></template>

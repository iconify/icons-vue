<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if0nh-buo.css';
import '../../css/b/b57rxsbat.css';
import '../../css/i/ivod1rbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":139.149,"height":111.25};
const content = `<path class="if0nh-buo"/><path class="b57rxsbat"/><path class="ivod1rbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:marimo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je7ywpbue.css';
import '../../css/v/v02n93nor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="je7ywpbue"/><path class="v02n93nor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-up-20-bold" /></template>

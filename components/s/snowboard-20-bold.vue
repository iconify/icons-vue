<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6pf78o6u.css';
import '../../css/n/njbgecbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r6pf78o6u"/><path class="njbgecbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snowboard-20-bold" /></template>

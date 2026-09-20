<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_-22ibss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_-22ibss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tasks-all" /></template>

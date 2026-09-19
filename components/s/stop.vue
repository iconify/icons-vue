<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isjxkebye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isjxkebye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:stop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wppiylbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="wppiylbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:tumblr" /></template>

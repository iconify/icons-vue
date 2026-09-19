<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3ks01b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="v3ks01b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:stop" /></template>

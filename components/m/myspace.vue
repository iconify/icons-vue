<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgu-rub7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":582,"height":674};
const content = `<path class="jgu-rub7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:myspace" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw7a82mon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xw7a82mon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tmux" /></template>

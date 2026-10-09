<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5fzb4bue.css';
import '../../css/i/iennupbfk.css';
import '../../css/z/ztja4fb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5fzb4bue"/><path class="iennupbfk"/><path class="ztja4fb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refresh-cw-48" /></template>

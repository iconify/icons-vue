<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh8pb8bip.css';
import '../../css/l/l19bqcctk.css';
import '../../css/c/cs433rzwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xh8pb8bip"/><path class="l19bqcctk"/><path class="cs433rzwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-plus-20" /></template>

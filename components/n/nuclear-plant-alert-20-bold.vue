<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey18pvvad.css';
import '../../css/c/cbw0uj2ck.css';
import '../../css/j/jeyqzjnhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ey18pvvad"/><path class="cbw0uj2ck"/><path class="jeyqzjnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-alert-20-bold" /></template>

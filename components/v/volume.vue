<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b66jsbpns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="b66jsbpns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:volume" /></template>

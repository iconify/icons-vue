<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9uu9lbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9uu9lbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:twitch" /></template>

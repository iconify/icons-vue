<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpe64o2wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wpe64o2wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speaker" /></template>

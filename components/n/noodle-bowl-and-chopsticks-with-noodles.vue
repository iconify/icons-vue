<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woy7o0ttp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="woy7o0ttp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:noodle-bowl-and-chopsticks-with-noodles" /></template>

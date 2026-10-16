<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbnqjxbpf.css';
import '../../css/r/rv6abjb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xbnqjxbpf"/><path class="rv6abjb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-speaker-20" /></template>

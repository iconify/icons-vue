<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hax53gbsh.css';
import '../../css/h/hb4lzh0lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hax53gbsh"/><path class="hb4lzh0lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trophy-circle-fill" /></template>

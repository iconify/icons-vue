<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb4h_tb7x.css';
import '../../css/e/eozwp4bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fb4h_tb7x"/><path class="eozwp4bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:stop" /></template>

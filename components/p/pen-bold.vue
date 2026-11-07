<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t66hbfb2l.css';
import '../../css/b/bkakk0bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t66hbfb2l"/><path class="bkakk0bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-bold" /></template>

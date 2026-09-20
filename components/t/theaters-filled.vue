<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsw7fgbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsw7fgbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:theaters-filled" /></template>

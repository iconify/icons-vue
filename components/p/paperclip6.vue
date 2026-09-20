<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qter91nah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qter91nah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paperclip6" /></template>

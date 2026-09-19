<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkq23losc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":669};
const content = `<path class="qkq23losc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:tabs" /></template>

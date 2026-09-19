<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr_ygns4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lr_ygns4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:minimize" /></template>

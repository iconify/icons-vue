<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwdn5hbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mwdn5hbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vermont" /></template>

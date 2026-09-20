<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh_rwubjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wh_rwubjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-finger-hold-remix" /></template>

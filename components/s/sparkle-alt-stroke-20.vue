<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqkp5ilzt.css';
import '../../css/z/zy3ocbcvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tqkp5ilzt"/><path class="zy3ocbcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sparkle-alt-stroke-20" /></template>

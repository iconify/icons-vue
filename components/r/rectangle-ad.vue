<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwe0zcczl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zwe0zcczl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rectangle-ad" /></template>

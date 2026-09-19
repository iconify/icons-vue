<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0k1xbo6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":614};
const content = `<path class="z0k1xbo6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:terminal" /></template>

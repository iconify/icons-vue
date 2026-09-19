<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3noic1wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3noic1wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:radio" /></template>

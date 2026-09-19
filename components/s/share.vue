<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc9f2b9-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zc9f2b9-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:share" /></template>

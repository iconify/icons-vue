<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlacyr9-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="wlacyr9-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:z" /></template>

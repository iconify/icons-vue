<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy_oq0bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yy_oq0bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-plus-outline" /></template>

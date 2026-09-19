<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3lxxbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yp3lxxbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:navigate-sharp" /></template>

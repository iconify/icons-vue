<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twe8hgzxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="twe8hgzxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:signal-slash" /></template>

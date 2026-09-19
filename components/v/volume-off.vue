<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkxw8zh6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="zkxw8zh6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:volume-off" /></template>

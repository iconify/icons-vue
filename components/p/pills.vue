<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go-j6fb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="go-j6fb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pills" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj5k6uu3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="aj5k6uu3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-slash" /></template>

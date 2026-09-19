<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0i8fc4rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x0i8fc4rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nsis-old" /></template>

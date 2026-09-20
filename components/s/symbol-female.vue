<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8ymuly4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m8ymuly4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:symbol-female" /></template>

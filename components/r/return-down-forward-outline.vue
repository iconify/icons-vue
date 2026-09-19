<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmbxl9aac.css';
import '../../css/z/z7rr8ngug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmbxl9aac"/><path class="z7rr8ngug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:return-down-forward-outline" /></template>

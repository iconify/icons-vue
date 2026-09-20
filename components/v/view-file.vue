<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmj5g9btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="lmj5g9btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:view-file" /></template>

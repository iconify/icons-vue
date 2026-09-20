<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x40v4sbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="x40v4sbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:message" /></template>

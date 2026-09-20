<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z16tn7gsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="z16tn7gsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:skip-to-start" /></template>

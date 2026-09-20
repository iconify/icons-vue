<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdu0sgbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hdu0sgbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:paid" /></template>

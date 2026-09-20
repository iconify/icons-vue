<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7vd29bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="r7vd29bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:sent" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgpqoo4op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="fgpqoo4op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:paperclamp" /></template>

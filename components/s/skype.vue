<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_9297i3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h_9297i3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:skype" /></template>

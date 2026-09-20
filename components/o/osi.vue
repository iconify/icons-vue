<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o40ncj9os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o40ncj9os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:osi" /></template>

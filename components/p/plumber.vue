<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3uiqy88h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w3uiqy88h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:plumber" /></template>

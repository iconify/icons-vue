<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-2g_-b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-2g_-b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:notificationtop" /></template>

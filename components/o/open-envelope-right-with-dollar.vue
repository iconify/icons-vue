<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhmb8zbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lhmb8zbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right-with-dollar" /></template>

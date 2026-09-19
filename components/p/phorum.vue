<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eonk5dneh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":895,"height":1025};
const content = `<path class="eonk5dneh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phorum" /></template>

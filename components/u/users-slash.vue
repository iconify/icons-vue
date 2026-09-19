<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn6614b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fn6614b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:users-slash" /></template>

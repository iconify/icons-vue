<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsj264bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":770,"height":1024};
const content = `<path class="hsj264bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:women" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esmh27b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="esmh27b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:workshirt" /></template>

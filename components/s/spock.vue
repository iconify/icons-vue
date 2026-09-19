<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcl50ybdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1025};
const content = `<path class="dcl50ybdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:spock" /></template>

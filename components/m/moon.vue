<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im91p0gan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="im91p0gan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:moon" /></template>

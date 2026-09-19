<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fubfasb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fubfasb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mitten" /></template>

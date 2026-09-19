<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ygf1shw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y1ygf1shw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:twoo" /></template>

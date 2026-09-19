<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv8o2pb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sv8o2pb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:micro-blog" /></template>

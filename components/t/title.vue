<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5i3ru5ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5i3ru5ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:title" /></template>

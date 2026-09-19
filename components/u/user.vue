<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq66orbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nq66orbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:user" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz97jizsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lz97jizsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rspec" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhvfa7b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="vhvfa7b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:toilet-portable" /></template>

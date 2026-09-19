<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wigy65mwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wigy65mwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-haskell" /></template>

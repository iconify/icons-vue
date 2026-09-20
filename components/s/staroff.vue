<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr43l9aex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mr43l9aex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:staroff" /></template>

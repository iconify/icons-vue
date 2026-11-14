<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag96bfbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ag96bfbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:qodo-wordmark" /></template>

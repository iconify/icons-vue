<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlsucpw_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dlsucpw_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:width" /></template>

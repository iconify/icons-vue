<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfa1xv1fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tfa1xv1fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:notion-logo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhclswmub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jhclswmub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tor" /></template>

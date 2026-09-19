<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmjq4kbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gmjq4kbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:terminal-secure" /></template>

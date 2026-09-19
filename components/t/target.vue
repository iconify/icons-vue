<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkaji56vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xkaji56vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:target" /></template>

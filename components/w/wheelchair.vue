<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9kcr3qkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j9kcr3qkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:wheelchair" /></template>

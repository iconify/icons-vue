<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx3j4ua7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx3j4ua7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vitepress" /></template>

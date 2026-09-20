<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr3kuvq0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr3kuvq0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:nuxt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5bgf6b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5bgf6b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:renren" /></template>

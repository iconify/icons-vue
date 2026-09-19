<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yenfskb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yenfskb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:xml" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljj7i8b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljj7i8b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:toaster" /></template>

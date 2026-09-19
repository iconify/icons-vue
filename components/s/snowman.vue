<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2mr-w8gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":833,"height":1024};
const content = `<path class="v2mr-w8gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:snowman" /></template>

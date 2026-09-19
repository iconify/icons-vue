<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8hrerbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="u8hrerbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:p" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhi6ye7ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="nhi6ye7ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:twofingerswipedown" /></template>

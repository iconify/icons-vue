<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3osvftpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w3osvftpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:octoloaderfour" /></template>

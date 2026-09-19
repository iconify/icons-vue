<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gljv7l19y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gljv7l19y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:restart" /></template>

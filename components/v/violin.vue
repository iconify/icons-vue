<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqg-62b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gqg-62b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:violin" /></template>

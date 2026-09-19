<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jts7qhbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jts7qhbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zikula" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc5x16b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oc5x16b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarezero" /></template>

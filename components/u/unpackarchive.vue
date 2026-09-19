<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaamf9vwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jaamf9vwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:unpackarchive" /></template>

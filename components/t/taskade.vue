<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh5ame3kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dh5ame3kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:taskade" /></template>

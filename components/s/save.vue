<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc8wj-c_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jc8wj-c_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:save" /></template>

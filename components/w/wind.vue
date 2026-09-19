<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fv8dtdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j7fv8dtdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wind" /></template>

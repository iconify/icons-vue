<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol8lpnb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="ol8lpnb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:vineapp" /></template>

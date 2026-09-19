<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ygy4hxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="f1ygy4hxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:navigation" /></template>

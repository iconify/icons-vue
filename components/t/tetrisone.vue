<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc8va39jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="mc8va39jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tetrisone" /></template>

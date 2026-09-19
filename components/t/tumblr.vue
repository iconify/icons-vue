<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk-s2w2fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tk-s2w2fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tumblr" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9f6c35gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="k9f6c35gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:q" /></template>

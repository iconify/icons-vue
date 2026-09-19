<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv7kcabzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wv7kcabzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pingpong" /></template>

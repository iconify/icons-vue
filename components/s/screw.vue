<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9j5sz1kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="s9j5sz1kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:screw" /></template>

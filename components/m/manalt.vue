<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luecgc8hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":1024};
const content = `<path class="luecgc8hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:manalt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrb4ktbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="zrb4ktbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mimetype" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpgx4vb3u.css';
import '../../css/b/bdkmogxxu.css';
import '../../css/d/d2rrvbcjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gpgx4vb3u"/><path class="bdkmogxxu"/><path class="d2rrvbcjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:run" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gstd5dbik.css';
import '../../css/j/j4hy2kb8r.css';
import '../../css/z/zn0v0yjgo.css';
import '../../css/a/axli2ab7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gstd5dbik"/><path class="j4hy2kb8r"/><path class="zn0v0yjgo"/><path class="axli2ab7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:musical-note" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brgyq0v3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="brgyq0v3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:moon" /></template>

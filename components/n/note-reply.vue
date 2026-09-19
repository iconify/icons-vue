<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lry9t6b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lry9t6b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:note-reply" /></template>

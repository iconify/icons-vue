<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2yezpb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":210,"height":700};
const content = `<path class="b2yezpb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:small-arrow-left" /></template>

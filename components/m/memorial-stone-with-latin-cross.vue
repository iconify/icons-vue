<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b186tqo6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b186tqo6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-latin-cross" /></template>

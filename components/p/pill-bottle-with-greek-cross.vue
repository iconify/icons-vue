<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0r6105yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b0r6105yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pill-bottle-with-greek-cross" /></template>

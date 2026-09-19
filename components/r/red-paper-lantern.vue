<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq35cqbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jq35cqbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-paper-lantern" /></template>

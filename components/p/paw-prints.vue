<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq7mt7e7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dq7mt7e7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:paw-prints" /></template>

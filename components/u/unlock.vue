<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1nqo117j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="g1nqo117j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:unlock" /></template>

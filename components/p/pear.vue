<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lke-3bb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lke-3bb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pear" /></template>

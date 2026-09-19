<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enich5jvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="enich5jvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sandwich" /></template>

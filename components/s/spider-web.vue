<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sftvdbcic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sftvdbcic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:spider-web" /></template>

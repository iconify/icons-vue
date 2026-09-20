<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhlsn0baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lhlsn0baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:whale" /></template>

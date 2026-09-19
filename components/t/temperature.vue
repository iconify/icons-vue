<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahdpb2baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="ahdpb2baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:temperature" /></template>

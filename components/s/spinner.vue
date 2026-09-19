<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1nk26b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1344};
const content = `<path class="n1nk26b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:spinner" /></template>

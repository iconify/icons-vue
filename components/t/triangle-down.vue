<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sklii6bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":700};
const content = `<path class="sklii6bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:triangle-down" /></template>

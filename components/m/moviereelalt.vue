<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x07p7ld2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x07p7ld2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moviereelalt" /></template>

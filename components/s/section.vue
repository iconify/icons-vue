<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt7gntd-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kt7gntd-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:section" /></template>

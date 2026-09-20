<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3z9cbmwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3z9cbmwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:open-16" /></template>

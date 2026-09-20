<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi9xwzxrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yi9xwzxrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:text-16" /></template>

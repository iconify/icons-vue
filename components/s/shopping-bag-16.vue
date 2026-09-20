<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhg79_kue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uhg79_kue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:shopping-bag-16" /></template>

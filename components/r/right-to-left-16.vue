<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci1u_l1tk.css';
import '../../css/a/aiuvj1b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ci1u_l1tk"/><path class="aiuvj1b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:right-to-left-16" /></template>

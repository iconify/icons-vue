<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1c4z18tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p1c4z18tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sad2" /></template>

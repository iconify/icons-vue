<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqu4ud82b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tqu4ud82b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pen-nib" /></template>

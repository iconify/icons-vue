<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-xld0_tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-xld0_tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:notes-16" /></template>

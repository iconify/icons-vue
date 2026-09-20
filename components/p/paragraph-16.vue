<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgohxxbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rgohxxbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paragraph-16" /></template>

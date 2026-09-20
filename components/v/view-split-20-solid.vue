<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocbd0c1lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ocbd0c1lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:view-split-20-solid" /></template>

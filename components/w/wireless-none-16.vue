<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfqf9xbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pfqf9xbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wireless-none-16" /></template>

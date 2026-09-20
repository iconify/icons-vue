<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-ns_tb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-ns_tb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:reply-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3q3sr33k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x3q3sr33k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right-with-yen-yuan" /></template>

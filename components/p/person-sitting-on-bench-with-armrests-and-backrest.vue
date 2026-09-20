<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on1pytb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="on1pytb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-on-bench-with-armrests-and-backrest" /></template>

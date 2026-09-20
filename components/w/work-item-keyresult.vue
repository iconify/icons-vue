<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hybfehb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hybfehb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-keyresult" /></template>

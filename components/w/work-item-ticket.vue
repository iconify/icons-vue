<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh-9m4blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xh-9m4blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-ticket" /></template>

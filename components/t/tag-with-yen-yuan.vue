<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dklxusbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dklxusbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-yen-yuan" /></template>

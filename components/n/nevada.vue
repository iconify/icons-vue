<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4850jj9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f4850jj9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nevada" /></template>

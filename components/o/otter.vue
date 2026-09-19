<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-j0nkb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f-j0nkb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:otter" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8pr1kb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8pr1kb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:terminal" /></template>

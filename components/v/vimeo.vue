<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7zs_nueb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j7zs_nueb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:vimeo" /></template>

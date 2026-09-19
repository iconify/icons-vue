<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcxr7fb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":446,"height":512};
const content = `<path class="rcxr7fb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rollup-old" /></template>

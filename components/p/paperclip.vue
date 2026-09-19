<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv7gvnbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cv7gvnbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:paperclip" /></template>

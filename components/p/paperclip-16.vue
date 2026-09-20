<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh4fvekho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kh4fvekho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:paperclip-16" /></template>

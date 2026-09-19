<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kli4ktnoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kli4ktnoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:paperclip" /></template>

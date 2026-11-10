<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh3o9_kqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gh3o9_kqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:trash-arrow-up-16-solid" /></template>

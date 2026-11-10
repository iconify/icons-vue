<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8286fbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w8286fbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-exclamation-16-solid" /></template>

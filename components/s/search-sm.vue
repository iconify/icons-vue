<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_fg_bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="ia_fg_bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:search-sm" /></template>

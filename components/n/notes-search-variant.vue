<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at8qymb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at8qymb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notes-search-variant" /></template>

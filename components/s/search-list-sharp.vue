<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq4gaac2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq4gaac2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-list-sharp" /></template>

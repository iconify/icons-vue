<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0iyyxii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un0iyyxii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-zoom-in-filled" /></template>

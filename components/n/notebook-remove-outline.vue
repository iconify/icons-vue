<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9t8oo_bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9t8oo_bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-remove-outline" /></template>

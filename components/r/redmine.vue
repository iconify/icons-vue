<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqmjjv-pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqmjjv-pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:redmine" /></template>

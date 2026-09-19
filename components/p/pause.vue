<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq064gb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bq064gb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pause" /></template>

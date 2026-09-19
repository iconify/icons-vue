<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wakghnbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wakghnbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tag-filled" /></template>

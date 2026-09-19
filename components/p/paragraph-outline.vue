<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhzvn0bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhzvn0bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:paragraph-outline" /></template>

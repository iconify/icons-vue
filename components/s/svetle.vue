<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izz_7wynk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izz_7wynk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:svetle" /></template>

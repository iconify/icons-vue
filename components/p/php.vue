<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh1vn_bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh1vn_bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:php" /></template>

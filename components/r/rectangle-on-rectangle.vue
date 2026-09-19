<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfrn8jbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sfrn8jbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-on-rectangle" /></template>

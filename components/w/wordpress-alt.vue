<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6qt5nqnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6qt5nqnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:wordpress-alt" /></template>

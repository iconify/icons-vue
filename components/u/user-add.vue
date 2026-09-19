<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcfyfkbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcfyfkbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:user-add" /></template>

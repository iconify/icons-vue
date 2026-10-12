<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs7fdz14b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7fdz14b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:siren-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sha7p4r6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sha7p4r6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:rewind-left-fill" /></template>

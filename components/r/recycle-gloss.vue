<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o59v4fb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o59v4fb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:recycle-gloss" /></template>

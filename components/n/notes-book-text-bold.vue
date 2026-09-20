<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxhblib2y.css';
import '../../css/e/e92p4ac2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxhblib2y"/><path class="e92p4ac2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:notes-book-text-bold" /></template>

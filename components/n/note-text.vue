<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x23aa1b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x23aa1b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:note-text" /></template>

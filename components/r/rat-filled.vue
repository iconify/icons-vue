<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu2rdxylr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nu2rdxylr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rat-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui-vjc08x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-vjc08x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:note-text-plus-line" /></template>

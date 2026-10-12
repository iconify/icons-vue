<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydc0qablw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc0qablw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rows-3-filled" /></template>

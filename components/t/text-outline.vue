<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anw8c2tnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anw8c2tnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:text-outline" /></template>

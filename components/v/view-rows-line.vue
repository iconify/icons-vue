<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9bipf0fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9bipf0fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:view-rows-line" /></template>

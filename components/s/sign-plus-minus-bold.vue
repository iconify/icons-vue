<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogta_je5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogta_je5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-minus-bold" /></template>

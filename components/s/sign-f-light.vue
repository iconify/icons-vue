<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t65n2-b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t65n2-b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-f-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwn1u0bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwn1u0bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-dashed-mouse-pointer-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elt_osbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elt_osbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sheet-filled" /></template>

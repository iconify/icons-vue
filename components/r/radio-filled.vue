<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrlnyzn3k.css';
import '../../css/z/z3hyr2b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrlnyzn3k"/><path class="z3hyr2b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-filled" /></template>

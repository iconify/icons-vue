<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqm22z9lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqm22z9lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:triangle-right-filled" /></template>

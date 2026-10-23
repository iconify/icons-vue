<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya4sl-brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya4sl-brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:perfume-bottle-filled" /></template>

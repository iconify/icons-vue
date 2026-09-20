<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdt_2mbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdt_2mbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:totvs" /></template>

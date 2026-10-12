<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8cln5bam.css';
import '../../css/j/j0iubn3mf.css';
import '../../css/i/is0qnibip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8cln5bam"/><path class="j0iubn3mf"/><path class="is0qnibip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-pen-filled" /></template>

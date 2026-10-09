<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o976p-bam.css';
import '../../css/s/scecasm2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o976p-bam"/><path class="scecasm2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:note-20" /></template>

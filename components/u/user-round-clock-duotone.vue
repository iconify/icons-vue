<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ix6o9jb3s.css';
import '../../css/n/nygcshbpy.css';
import '../../css/i/iogsahb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ix6o9jb3s"/><path class="nygcshbpy"/><path class="iogsahb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-clock-duotone" /></template>

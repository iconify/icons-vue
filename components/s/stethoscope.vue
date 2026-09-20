<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbm918b9c.css';
import '../../css/n/n7kkcye_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbm918b9c"/><path class="n7kkcye_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:stethoscope" /></template>

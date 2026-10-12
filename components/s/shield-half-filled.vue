<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsixo77yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsixo77yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-half-filled" /></template>

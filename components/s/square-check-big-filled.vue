<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv_vc_2oq.css';
import '../../css/l/lgjscu5ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv_vc_2oq"/><path class="lgjscu5ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-check-big-filled" /></template>

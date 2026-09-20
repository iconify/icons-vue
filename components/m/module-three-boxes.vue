<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0tg69brx.css';
import '../../css/e/ed2t64tga.css';
import '../../css/f/fq7vapbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0tg69brx"/><path class="ed2t64tga"/><path class="fq7vapbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:module-three-boxes" /></template>

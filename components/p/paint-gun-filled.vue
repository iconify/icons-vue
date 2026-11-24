<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivw2o-sty.css';
import '../../css/i/i4_d93b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ivw2o-sty"/><path class="i4_d93b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paint-gun-filled" /></template>

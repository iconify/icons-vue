<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9abw714l.css';
import '../../css/o/oulxfua7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9abw714l"/><path clip-rule="evenodd" class="oulxfua7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mimatic" /></template>

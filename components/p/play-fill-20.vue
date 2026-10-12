<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbr-zzb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hbr-zzb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-fill-20" /></template>

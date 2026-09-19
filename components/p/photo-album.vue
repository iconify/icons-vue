<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye_oo_m6x.css';
import '../../css/a/ab89kobbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye_oo_m6x"/><path class="ab89kobbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:photo-album" /></template>

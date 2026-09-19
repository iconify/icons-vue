<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4ubkji_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4ubkji_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shuffle-2-outline" /></template>

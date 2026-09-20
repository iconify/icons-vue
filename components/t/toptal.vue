<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi_f7v6xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi_f7v6xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:toptal" /></template>

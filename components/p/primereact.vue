<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhml_382w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhml_382w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:primereact" /></template>

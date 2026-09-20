<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl9nb_96w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sl9nb_96w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ms-excel-outline" /></template>

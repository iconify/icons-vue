<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy30hqbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy30hqbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maserati" /></template>

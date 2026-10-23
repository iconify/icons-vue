<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi4o4ac1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi4o4ac1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sos" /></template>

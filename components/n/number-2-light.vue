<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-um4sufk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-um4sufk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-2-light" /></template>

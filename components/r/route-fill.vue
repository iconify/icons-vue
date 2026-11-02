<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkl1p4bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkl1p4bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:route-fill" /></template>

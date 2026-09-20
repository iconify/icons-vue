<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v59ziwbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v59ziwbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sololearn" /></template>

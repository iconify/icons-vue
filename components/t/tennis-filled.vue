<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il_o2nbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il_o2nbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tennis-filled" /></template>

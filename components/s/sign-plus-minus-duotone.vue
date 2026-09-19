<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sng-n9b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sng-n9b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-minus-duotone" /></template>

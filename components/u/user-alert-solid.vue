<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr5lswbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr5lswbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-alert-solid" /></template>

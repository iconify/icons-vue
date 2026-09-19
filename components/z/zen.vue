<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emfql_bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emfql_bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zen" /></template>

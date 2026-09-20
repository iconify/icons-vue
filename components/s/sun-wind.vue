<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eub4bub4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eub4bub4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sun-wind" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqn_vacfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqn_vacfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:route-filled" /></template>

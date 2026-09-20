<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arekppqws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arekppqws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:reserved-line" /></template>

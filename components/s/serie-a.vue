<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okmv9tbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okmv9tbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:serie-a" /></template>

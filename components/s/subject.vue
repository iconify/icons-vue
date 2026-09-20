<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hje_cmbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hje_cmbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:subject" /></template>

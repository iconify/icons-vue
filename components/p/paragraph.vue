<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kje-6ph0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kje-6ph0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:paragraph" /></template>

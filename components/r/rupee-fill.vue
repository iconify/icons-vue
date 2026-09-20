<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0lt7xb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0lt7xb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:rupee-fill" /></template>

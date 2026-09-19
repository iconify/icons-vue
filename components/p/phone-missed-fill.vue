<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz78egceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz78egceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:phone-missed-fill" /></template>

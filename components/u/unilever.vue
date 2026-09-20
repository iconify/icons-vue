<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu1uu_ppc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu1uu_ppc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unilever" /></template>

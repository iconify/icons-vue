<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br4xxmb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br4xxmb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-pos-minus" /></template>

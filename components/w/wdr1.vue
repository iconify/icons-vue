<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgh33qb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh33qb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wdr1" /></template>

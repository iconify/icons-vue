<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xe53owbmy.css';
import '../../css/g/gm84d-bws.css';
import '../../css/z/zopjch_2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle transform="rotate(90 12 5)" class="xe53owbmy"/><circle transform="rotate(90 12 12)" class="gm84d-bws"/><circle transform="rotate(90 12 19)" class="zopjch_2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-vertical-line-duotone" /></template>

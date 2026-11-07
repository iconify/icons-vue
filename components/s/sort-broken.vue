<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eq1qy8wwa.css';
import '../../css/f/f3o8v2b6s.css';
import '../../css/f/fml2qzxuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eq1qy8wwa"/><path class="f3o8v2b6s"/><path class="fml2qzxuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-broken" /></template>

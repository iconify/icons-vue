<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozbstuboh.css';
import '../../css/u/u3e4gfbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ozbstuboh"/><path class="u3e4gfbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-missed-20-bold" /></template>

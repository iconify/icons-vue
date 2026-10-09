<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ftczb6h.css';
import '../../css/j/jr9qnkhrr.css';
import '../../css/a/abgd3hbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ftczb6h"/><path class="jr9qnkhrr"/><path class="abgd3hbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-up-48" /></template>

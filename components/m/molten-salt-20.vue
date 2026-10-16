<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqfw9ounj.css';
import '../../css/v/v9iy7tbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqfw9ounj"/><path class="v9iy7tbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:molten-salt-20" /></template>

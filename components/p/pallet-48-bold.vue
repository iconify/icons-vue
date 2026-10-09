<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be6_u9f6k.css';
import '../../css/b/b_4t_bc2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="be6_u9f6k"/><path class="b_4t_bc2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pallet-48-bold" /></template>

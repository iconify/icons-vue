<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc2_l_b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lc2_l_b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-pause-fill-20" /></template>

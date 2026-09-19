<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwsul_b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwsul_b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:popsicle" /></template>

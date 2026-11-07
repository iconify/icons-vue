<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3n43-bnv.css';
import '../../css/l/lax56ybee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3n43-bnv"/><path class="lax56ybee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-minimalistic-2-bold" /></template>

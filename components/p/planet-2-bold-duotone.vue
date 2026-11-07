<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2m6oob6i.css';
import '../../css/u/uoyje9-pu.css';
import '../../css/y/y0d-blzxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2m6oob6i"/><path class="uoyje9-pu"/><path clip-rule="evenodd" class="y0d-blzxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-2-bold-duotone" /></template>

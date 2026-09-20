<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj3h9ft4y.css';
import '../../css/d/d2x1331fj.css';
import '../../css/u/uii4avzkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj3h9ft4y"/><circle class="d2x1331fj"/><circle class="uii4avzkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:shopping-cart" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulrix6h0r.css';
import '../../css/o/opnueljba.css';
import '../../css/t/t7w90pktp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulrix6h0r"/><path class="opnueljba"/><path class="t7w90pktp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-format-bold-duotone" /></template>

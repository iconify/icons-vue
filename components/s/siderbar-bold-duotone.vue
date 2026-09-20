<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o75u76x7m.css';
import '../../css/u/u0uqtx1rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o75u76x7m"/><path class="u0uqtx1rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siderbar-bold-duotone" /></template>

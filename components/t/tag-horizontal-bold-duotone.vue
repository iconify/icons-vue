<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opx7yx7he.css';
import '../../css/e/ecc5nebhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opx7yx7he"/><path class="ecc5nebhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-horizontal-bold-duotone" /></template>

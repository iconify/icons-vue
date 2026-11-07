<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg_fn_bfr.css';
import '../../css/z/z3e729uop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg_fn_bfr"/><path class="z3e729uop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toolbox-bold-duotone" /></template>

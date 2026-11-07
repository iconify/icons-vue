<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctu7he3ei.css';
import '../../css/m/mrqs5-_hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctu7he3ei"/><path class="mrqs5-_hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-forward-bold-duotone" /></template>

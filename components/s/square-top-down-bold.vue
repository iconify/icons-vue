<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1imhmbtv.css';
import '../../css/l/l7647cc_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e1imhmbtv"/><path class="l7647cc_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-top-down-bold" /></template>

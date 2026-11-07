<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gry2dppuz.css';
import '../../css/l/lm1gwl2sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gry2dppuz"/><path class="lm1gwl2sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-bold-duotone" /></template>

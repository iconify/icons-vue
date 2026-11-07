<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkwop1f3g.css';
import '../../css/r/romiv8ccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkwop1f3g"/><path class="romiv8ccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-left-up-bold-duotone" /></template>

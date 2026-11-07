<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esxisibaw.css';
import '../../css/u/ud65eiioe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="esxisibaw"/><path class="ud65eiioe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbon-bold-duotone" /></template>

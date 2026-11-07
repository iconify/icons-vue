<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay5dbdcag.css';
import '../../css/e/emvqbbbmt.css';
import '../../css/k/kg0jzztbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5dbdcag"/><path clip-rule="evenodd" class="emvqbbbmt"/><path class="kg0jzztbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stretching-round-bold-duotone" /></template>

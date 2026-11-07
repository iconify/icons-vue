<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvqe86bhm.css';
import '../../css/i/ibf2r7bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvqe86bhm"/><path class="ibf2r7bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-circle-bold-duotone" /></template>

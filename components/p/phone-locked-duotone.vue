<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb7_855gm.css';
import '../../css/t/tu53urjhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb7_855gm"/><path class="tu53urjhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-locked-duotone" /></template>

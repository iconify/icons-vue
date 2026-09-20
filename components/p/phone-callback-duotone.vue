<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb7_855gm.css';
import '../../css/i/ipbkl_l6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb7_855gm"/><path class="ipbkl_l6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-callback-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yssci-bbg.css';
import '../../css/i/igpj62s2p.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGDrELLdDM"><g class="ft5dv1b6b"><path class="yssci-bbg"/><path class="igpj62s2p"/></g></mask></defs><path mask="url(#SVGDrELLdDM)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sign-in-squre-duotone-line" /></template>

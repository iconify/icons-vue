<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o58hkebvg.css';
import '../../css/v/v7rtunbwn.css';
import '../../css/t/tu6hf7byk.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGfGA9Aeaq"><g class="o58hkebvg"><path class="v7rtunbwn"/><path class="tu6hf7byk"/></g></mask></defs><path mask="url(#SVGfGA9Aeaq)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:road-alt-duotone-line" /></template>

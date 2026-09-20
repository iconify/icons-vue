<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjnoqlmbw.css';
import '../../css/m/mw0oakbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjnoqlmbw"/><path class="mw0oakbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:shopping-cart-trolley-full" /></template>

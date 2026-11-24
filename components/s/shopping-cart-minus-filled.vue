<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pud5wbbsm.css';
import '../../css/p/ppmoggy1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pud5wbbsm"/><path class="ppmoggy1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-cart-minus-filled" /></template>

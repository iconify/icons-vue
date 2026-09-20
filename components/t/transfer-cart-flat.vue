<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/ltfqsqjkt.css';
import '../../css/d/dtuk-4b7n.css';
import '../../css/z/z9aamlbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ltfqsqjkt"/><path class="dtuk-4b7n"/><path class="z9aamlbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:transfer-cart-flat" /></template>

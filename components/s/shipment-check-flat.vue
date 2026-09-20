<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pyk5dibjj.css';
import '../../css/c/cwbz9hv9b.css';
import '../../css/s/s9-lr8ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pyk5dibjj"/><path class="cwbz9hv9b"/><path class="s9-lr8ber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:shipment-check-flat" /></template>

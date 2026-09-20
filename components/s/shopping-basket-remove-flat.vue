<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vy6frvpsh.css';
import '../../css/l/ltxit21ma.css';
import '../../css/z/z9j_ljb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vy6frvpsh"/><path class="ltxit21ma"/><path class="z9j_ljb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:shopping-basket-remove-flat" /></template>

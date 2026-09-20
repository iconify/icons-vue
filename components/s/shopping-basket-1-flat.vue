<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vm5w9mb2f.css';
import '../../css/l/l7h62c3sj.css';
import '../../css/h/hr1mwlb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vm5w9mb2f"/><path class="l7h62c3sj"/><path class="hr1mwlb4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:shopping-basket-1-flat" /></template>

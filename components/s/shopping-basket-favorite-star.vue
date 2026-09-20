<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m-9hukb0h.css';
import '../../css/r/rg85h1bjt.css';
import '../../css/y/yq35egede.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m-9hukb0h"/><path class="rg85h1bjt"/><path class="yq35egede"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-basket-favorite-star" /></template>

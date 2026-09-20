<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g6k77kbns.css';
import '../../css/x/x-k3sknjq.css';
import '../../css/b/brqbnxbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g6k77kbns"/><path class="x-k3sknjq"/><path class="brqbnxbtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-cart-trolley-upload" /></template>

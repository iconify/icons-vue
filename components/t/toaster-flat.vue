<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dd6gkfwme.css';
import '../../css/z/zi7qyobeq.css';
import '../../css/h/hjezvpw5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dd6gkfwme"/><path class="zi7qyobeq"/><path class="hjezvpw5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:toaster-flat" /></template>

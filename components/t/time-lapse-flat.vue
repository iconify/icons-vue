<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rhfeptotx.css';
import '../../css/o/obwtx-c8u.css';
import '../../css/v/vef42hohb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rhfeptotx"/><path class="obwtx-c8u"/><path class="vef42hohb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:time-lapse-flat" /></template>

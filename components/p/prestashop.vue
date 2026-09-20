<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlrgcccrm.css';
import '../../css/o/oqhmv740i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlrgcccrm"/><path class="oqhmv740i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prestashop" /></template>

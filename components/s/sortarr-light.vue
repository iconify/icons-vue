<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra6wx1tpy.css';
import '../../css/h/h5po_umnf.css';
import '../../css/a/a-z8z7pww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ra6wx1tpy"/><path class="h5po_umnf"/><path class="a-z8z7pww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortarr-light" /></template>

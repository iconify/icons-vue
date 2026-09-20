<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyfuw7bce.css';
import '../../css/i/iu0eltnal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xyfuw7bce"/><path class="iu0eltnal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:rain" /></template>

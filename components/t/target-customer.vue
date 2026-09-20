<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgjdvv67z.css';
import '../../css/t/ttm_7fxim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pgjdvv67z"/><path class="ttm_7fxim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:target-customer" /></template>

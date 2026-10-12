<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhpma-sca.css';
import '../../css/k/kyb_5vwwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vhpma-sca"/><path class="kyb_5vwwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:trash-stroke-20" /></template>

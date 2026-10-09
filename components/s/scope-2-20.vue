<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcck3kbsm.css';
import '../../css/s/sarzorbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zcck3kbsm"/><path class="sarzorbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scope-2-20" /></template>

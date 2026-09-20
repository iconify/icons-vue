<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg8lg1b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="kg8lg1b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:researcherid" /></template>

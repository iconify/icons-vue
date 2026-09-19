<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azscm5t4y.css';
import '../../css/q/qqfentbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="azscm5t4y"/><path class="qqfentbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:right-down2" /></template>

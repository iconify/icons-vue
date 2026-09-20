<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmqdv8bhv.css';
import '../../css/p/pqncy4b2j.css';
import '../../css/z/z7h6iq1vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kmqdv8bhv"/><path class="pqncy4b2j"/><path class="z7h6iq1vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:uml" /></template>

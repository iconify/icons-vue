<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prmy9wtgl.css';
import '../../css/t/t8vej38_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prmy9wtgl"/><path class="t8vej38_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:senlo-light" /></template>

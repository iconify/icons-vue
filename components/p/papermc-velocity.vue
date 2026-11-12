<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n73j_hptb.css';
import '../../css/i/i3zqipbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n73j_hptb"/><path class="i3zqipbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-velocity" /></template>

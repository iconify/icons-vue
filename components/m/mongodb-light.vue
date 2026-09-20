<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcd13orep.css';
import '../../css/z/zs9x5hotx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kcd13orep"/><path class="zs9x5hotx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mongodb-light" /></template>

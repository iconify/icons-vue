<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk7iwbbts.css';
import '../../css/l/lprgm5wxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk7iwbbts"/><path class="lprgm5wxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ultimate-certificate-manager-dark" /></template>

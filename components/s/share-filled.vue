<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8_j0_bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8_j0_bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:share-filled" /></template>

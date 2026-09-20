<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coh2acbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="coh2acbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stump-dark" /></template>

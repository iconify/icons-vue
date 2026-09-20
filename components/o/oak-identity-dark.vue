<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6bi1rard.css';
import '../../css/m/m5qdqtwec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6bi1rard"/><path class="m5qdqtwec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oak-identity-dark" /></template>

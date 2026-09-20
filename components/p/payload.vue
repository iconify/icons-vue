<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iycln-b8i.css';
import '../../css/d/da-apvk5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="da-apvk5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:payload" /></template>

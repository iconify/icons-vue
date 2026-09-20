<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm7ss7bki.css';
import '../../css/g/gm0rcf1lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rm7ss7bki"/><path class="gm0rcf1lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reactflux" /></template>

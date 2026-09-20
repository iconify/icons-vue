<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smlohmbtr.css';
import '../../css/u/u79s_5bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smlohmbtr"/><path class="u79s_5bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posteria-light" /></template>

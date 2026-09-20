<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvjmzfm2h.css';
import '../../css/a/ay64in9vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvjmzfm2h"/><path class="ay64in9vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surfshark" /></template>

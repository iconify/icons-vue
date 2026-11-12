<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2b4j_7ld.css';
import '../../css/b/bd6wcc_tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2b4j_7ld"/><path class="bd6wcc_tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:virtualbox-light" /></template>

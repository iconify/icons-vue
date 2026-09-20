<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1hm4ub9h.css';
import '../../css/b/bd6wcc_tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1hm4ub9h"/><path class="bd6wcc_tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:virtualbox-light" /></template>

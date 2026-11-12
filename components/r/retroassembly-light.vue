<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9rc3cc_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9rc3cc_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retroassembly-light" /></template>

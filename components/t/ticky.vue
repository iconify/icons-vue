<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u57lmtb4w.css';
import '../../css/g/gprn__pii.css';
import '../../css/d/de8upybhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u57lmtb4w"/><path class="gprn__pii"/><path class="de8upybhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticky" /></template>

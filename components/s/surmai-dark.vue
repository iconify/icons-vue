<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqdbazo-e.css';
import '../../css/a/a0a2rfb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqdbazo-e"/><path class="a0a2rfb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surmai-dark" /></template>

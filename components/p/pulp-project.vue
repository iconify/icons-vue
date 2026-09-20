<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkwkh496s.css';
import '../../css/u/u8-785b1v.css';
import '../../css/b/bni3nanaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkwkh496s"/><path class="u8-785b1v"/><path class="bni3nanaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pulp-project" /></template>

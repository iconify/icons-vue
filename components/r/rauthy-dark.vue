<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk9zn-beg.css';
import '../../css/w/w-xcclbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk9zn-beg"/><path class="w-xcclbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rauthy-dark" /></template>

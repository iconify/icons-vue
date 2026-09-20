<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oto715bfm.css';
import '../../css/g/gnj61ac6v.css';
import '../../css/o/orctz5b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oto715bfm"/><path class="gnj61ac6v"/><path class="orctz5b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smore-newsletter" /></template>

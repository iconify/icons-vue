<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzxio8blc.css';
import '../../css/t/tsv_okbow.css';
import '../../css/i/ij824bc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rzxio8blc"/><path class="tsv_okbow"/><circle class="ij824bc0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rurdesk-dark" /></template>

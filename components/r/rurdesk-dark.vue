<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg676pb3g.css';
import '../../css/t/tsv_okbow.css';
import '../../css/s/sclwzib1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rg676pb3g"/><path class="tsv_okbow"/><circle class="sclwzib1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rurdesk-dark" /></template>

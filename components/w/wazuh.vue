<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he3q-t8yh.css';
import '../../css/a/atcx61-tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="he3q-t8yh"/><circle class="atcx61-tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wazuh" /></template>

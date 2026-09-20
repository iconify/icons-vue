<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_7fzobku.css';
import '../../css/g/gw9s8899s.css';
import '../../css/t/t616afbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="l_7fzobku"/><circle class="gw9s8899s"/><circle class="t616afbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smlight-light" /></template>

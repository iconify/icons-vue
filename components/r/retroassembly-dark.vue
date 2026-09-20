<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnqppabfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnqppabfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retroassembly-dark" /></template>

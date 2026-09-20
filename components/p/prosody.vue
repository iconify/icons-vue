<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aonepje_a.css';
import '../../css/h/h0wavjb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aonepje_a"/><path class="h0wavjb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prosody" /></template>

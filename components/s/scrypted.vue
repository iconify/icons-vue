<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a21bjysuj.css';
import '../../css/t/tm-9qcpcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a21bjysuj"/><path class="tm-9qcpcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrypted" /></template>

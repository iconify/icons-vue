<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqyns6bnn.css';
import '../../css/n/n75ow_brw.css';
import '../../css/w/wpkm073zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqyns6bnn"/><path class="n75ow_brw"/><path class="wpkm073zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trailarr-light" /></template>

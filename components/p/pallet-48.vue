<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcp2pkb_d.css';
import '../../css/a/acu1a62dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcp2pkb_d"/><path class="acu1a62dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pallet-48" /></template>

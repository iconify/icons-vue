<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za30h5bbb.css';
import '../../css/f/f7qu89bfn.css';
import '../../css/n/nzc3r4b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="za30h5bbb"/><path class="f7qu89bfn"/><path class="nzc3r4b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workspace-48" /></template>

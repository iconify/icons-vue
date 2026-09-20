<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kji3f8xww.css';
import '../../css/m/m0_ghw2pl.css';
import '../../css/i/ietn-5oir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kji3f8xww"/><circle class="m0_ghw2pl"/><path class="ietn-5oir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:systemd-light" /></template>

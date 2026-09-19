<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftyrjsbkc.css';
import '../../css/r/rjqqyp-nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftyrjsbkc"/><path class="rjqqyp-nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:network-file-system-outlined" /></template>

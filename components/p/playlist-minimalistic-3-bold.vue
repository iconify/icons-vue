<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siidedcrr.css';
import '../../css/v/vcg1j4bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="siidedcrr"/><path class="vcg1j4bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-3-bold" /></template>

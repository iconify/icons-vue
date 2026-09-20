<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbn_t3z4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbn_t3z4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-email" /></template>

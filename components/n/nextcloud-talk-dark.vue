<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_j778rnr.css';
import '../../css/h/huj_k0bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n_j778rnr"/><path clip-rule="evenodd" class="huj_k0bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-talk-dark" /></template>

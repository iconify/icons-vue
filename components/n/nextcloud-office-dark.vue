<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf79mvbno.css';
import '../../css/n/nq01l99qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uf79mvbno"/><path clip-rule="evenodd" class="nq01l99qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-dark" /></template>

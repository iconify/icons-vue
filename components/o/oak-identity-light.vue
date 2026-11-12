<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry8edhbmf.css';
import '../../css/p/ps1262b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ry8edhbmf"/><path class="ps1262b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oak-identity-light" /></template>

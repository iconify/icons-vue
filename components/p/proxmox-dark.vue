<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_yo0bqco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_yo0bqco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmox-dark" /></template>

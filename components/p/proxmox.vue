<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2o94vbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2o94vbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:proxmox" /></template>

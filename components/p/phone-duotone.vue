<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7e9-ibfi.css';
import '../../css/k/ksyanacfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7e9-ibfi"/><path clip-rule="evenodd" class="ksyanacfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:phone-duotone" /></template>

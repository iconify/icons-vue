<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf8cknr0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wf8cknr0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plus-duotone" /></template>

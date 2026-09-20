<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzly_lbpi.css';
import '../../css/u/uh68dtbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzly_lbpi"/><path class="uh68dtbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:steam" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf83xubvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pf83xubvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:mat" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv_9jiofm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fv_9jiofm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:table-rows-fill" /></template>

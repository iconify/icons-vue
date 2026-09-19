<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrk853yos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrk853yos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:percent-outline" /></template>

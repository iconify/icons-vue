<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srf3omgjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srf3omgjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-2-broken" /></template>

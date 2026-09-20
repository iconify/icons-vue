<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npis9_bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npis9_bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:zcool-logo-1-solid" /></template>

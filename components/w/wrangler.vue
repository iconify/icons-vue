<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi269-bum.css';
import '../../css/r/rk3z2_bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yi269-bum"/><path class="rk3z2_bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:wrangler" /></template>

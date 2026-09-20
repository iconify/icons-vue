<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ds3ebdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v_ds3ebdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shield" /></template>

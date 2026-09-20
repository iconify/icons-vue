<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v02pqccpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v02pqccpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wind-outline" /></template>

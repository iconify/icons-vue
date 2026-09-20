<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5_3hdchp.css';
import '../../css/v/vlf_obbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5_3hdchp"/><path class="vlf_obbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mc" /></template>

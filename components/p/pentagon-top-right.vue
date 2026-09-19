<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pou4mbcvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pou4mbcvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pentagon-top-right" /></template>

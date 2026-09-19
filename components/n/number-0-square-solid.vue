<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozis5k_fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozis5k_fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-0-square-solid" /></template>

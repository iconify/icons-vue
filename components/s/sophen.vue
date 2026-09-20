<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pib_0mbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pib_0mbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sophen" /></template>

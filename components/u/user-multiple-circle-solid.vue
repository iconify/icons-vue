<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow1beibmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ow1beibmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-multiple-circle-solid" /></template>

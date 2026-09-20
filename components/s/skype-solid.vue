<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym_l82hyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym_l82hyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:skype-solid" /></template>

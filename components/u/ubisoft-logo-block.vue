<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du_ov4bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="du_ov4bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ubisoft-logo-block" /></template>

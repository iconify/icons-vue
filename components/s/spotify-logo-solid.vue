<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhdlglbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhdlglbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:spotify-logo-solid" /></template>

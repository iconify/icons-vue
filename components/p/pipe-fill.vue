<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlcn_2b3l.css';
import '../../css/f/f7l70zbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dlcn_2b3l"/><path class="f7l70zbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pipe-fill" /></template>

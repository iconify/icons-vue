<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5dn8xbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s5dn8xbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:virus-antivirus-solid" /></template>

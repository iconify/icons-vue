<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3v5spfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm3v5spfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wifi-low-solid" /></template>

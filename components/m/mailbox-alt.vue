<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulus40b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulus40b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:mailbox-alt" /></template>

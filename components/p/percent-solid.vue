<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax0xbjb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax0xbjb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:percent-solid" /></template>

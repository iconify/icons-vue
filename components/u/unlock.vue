<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibeovbccp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibeovbccp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:unlock" /></template>

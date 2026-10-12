<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwd45ta4x.css';
import '../../css/x/xjwgdc_uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwd45ta4x"/><path clip-rule="evenodd" class="xjwgdc_uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vault-filled" /></template>

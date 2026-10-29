<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaq68ebxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaq68ebxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-2-solid" /></template>

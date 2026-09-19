<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs3ol7bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs3ol7bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-check-solid" /></template>

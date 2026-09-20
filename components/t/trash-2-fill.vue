<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhxig0hap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhxig0hap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trash-2-fill" /></template>

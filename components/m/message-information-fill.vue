<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfcjhcclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfcjhcclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-information-fill" /></template>

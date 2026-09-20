<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrmddmjov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrmddmjov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-minus-round-fill" /></template>

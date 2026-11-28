<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t18l18ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t18l18ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-x" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmzezlmhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmzezlmhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-outgoing-fill" /></template>

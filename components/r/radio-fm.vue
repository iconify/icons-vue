<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcmrx9q_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcmrx9q_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radio-fm" /></template>

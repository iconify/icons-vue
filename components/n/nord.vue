<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pid1qrb3p.css';
import '../../css/j/jng12gler.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pid1qrb3p"/><path class="jng12gler"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nord" /></template>

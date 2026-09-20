<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g69n6e39t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g69n6e39t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:shield-check" /></template>

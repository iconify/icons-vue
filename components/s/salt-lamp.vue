<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1r6vzg8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1r6vzg8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:salt-lamp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5vu1ld5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5vu1ld5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:robinhood" /></template>

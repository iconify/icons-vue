<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avc-ejbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avc-ejbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:wave-signal" /></template>

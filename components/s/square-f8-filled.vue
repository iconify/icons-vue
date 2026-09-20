<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrf2rnkcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrf2rnkcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-f8-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvk-gobvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvk-gobvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:skoda" /></template>

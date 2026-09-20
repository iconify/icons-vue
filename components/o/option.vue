<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrhp-e1vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrhp-e1vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:option" /></template>

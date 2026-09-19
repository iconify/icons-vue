<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onzcvab0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onzcvab0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-frontdoor-open" /></template>

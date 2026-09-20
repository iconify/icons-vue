<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieffhn-ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieffhn-ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-arrow-down-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eck_0ccib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eck_0ccib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-voice" /></template>

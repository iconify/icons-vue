<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfw2-nb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qfw2-nb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sign-language" /></template>

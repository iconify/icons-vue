<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqvks2byp.css';
import '../../css/t/tgpt75tqs.css';
import '../../css/v/v03hklb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqvks2byp wm-k"/><path class="tgpt75tqs wm-a"/><path class="v03hklb9o wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:receipt" /></template>

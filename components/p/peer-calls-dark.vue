<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q36h1kl5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q36h1kl5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peer-calls-dark" /></template>

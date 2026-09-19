<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4nfscq4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q4nfscq4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pulsar" /></template>

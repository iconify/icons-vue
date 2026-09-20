<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1qap0bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="g1qap0bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vr-headset-solid" /></template>

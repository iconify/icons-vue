<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snr1ktbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="snr1ktbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sass" /></template>

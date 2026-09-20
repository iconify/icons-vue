<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz6ow9y5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fz6ow9y5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-email-expressive" /></template>

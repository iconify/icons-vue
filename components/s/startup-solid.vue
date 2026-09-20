<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1u2psb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1u2psb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:startup-solid" /></template>

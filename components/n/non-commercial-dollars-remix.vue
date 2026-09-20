<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrj6jqbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrj6jqbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:non-commercial-dollars-remix" /></template>

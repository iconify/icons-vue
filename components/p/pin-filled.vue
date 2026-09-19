<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bliqavuzu.css';
import '../../css/u/uk1d9ew2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="bliqavuzu"/><path class="uk1d9ew2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pin-filled" /></template>

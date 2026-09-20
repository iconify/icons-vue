<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_0df65aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_0df65aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:workersai-cloudflare" /></template>

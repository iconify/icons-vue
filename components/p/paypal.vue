<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5rg4yowh.css';
import '../../css/n/nexfdi4-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5rg4yowh"/><path class="nexfdi4-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:paypal" /></template>

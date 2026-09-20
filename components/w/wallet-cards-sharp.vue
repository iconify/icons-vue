<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykze3k15m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykze3k15m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards-sharp" /></template>

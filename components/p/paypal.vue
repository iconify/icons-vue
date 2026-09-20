<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc05y9bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc05y9bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:paypal" /></template>

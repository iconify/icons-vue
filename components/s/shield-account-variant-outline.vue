<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umtojzbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umtojzbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-account-variant-outline" /></template>

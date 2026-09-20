<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anupi1uga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anupi1uga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-broken" /></template>

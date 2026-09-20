<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo60o6k2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo60o6k2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:phone-off" /></template>

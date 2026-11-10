<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vew8owk2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vew8owk2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:zeta" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krawmvbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krawmvbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:mobile-phone-blackberry-2-bold" /></template>

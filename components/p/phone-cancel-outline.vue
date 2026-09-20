<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwhh8jslo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwhh8jslo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-cancel-outline" /></template>

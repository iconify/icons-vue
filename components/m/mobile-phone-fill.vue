<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4wxyjb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4wxyjb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:mobile-phone-fill" /></template>

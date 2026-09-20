<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyro86bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyro86bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vespa-electric-outline" /></template>

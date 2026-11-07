<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk5kasbyr.css';
import '../../css/i/idnpklgal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk5kasbyr"/><path class="idnpklgal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transfer-vertical-bold" /></template>

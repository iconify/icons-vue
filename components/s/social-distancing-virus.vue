<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isb_zrb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isb_zrb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:social-distancing-virus" /></template>

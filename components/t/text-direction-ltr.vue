<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_pf2en7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_pf2en7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-direction-ltr" /></template>

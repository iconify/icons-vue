<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs_pu7psi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs_pu7psi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus-solid" /></template>
